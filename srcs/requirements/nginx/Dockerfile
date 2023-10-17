FROM debian:bullseye
ARG CERT_PATH
ARG KEY_PATH

RUN apt-get update -y && apt-get upgrade -y \
   && apt-get -y install nginx  openssl gettext

COPY ./conf/nginx.conf /tmp/
RUN envsubst '$CERT_PATH,$KEY_PATH' < /tmp/nginx.conf > /etc/nginx/conf.d/nginx.conf

RUN openssl req -x509 -nodes -out mkovoor.crt -keyout mkovoor.key \
	-subj "/C=FR/ST=IDF/L=AD/O=42/OU=42/CN=mkovoor.42.fr/UID=mkovoor" \
	&& mv mkovoor.crt ${CERT_PATH}/ && mv mkovoor.key ${KEY_PATH}/
EXPOSE 443 

CMD ["nginx", "-g", "daemon off;"]