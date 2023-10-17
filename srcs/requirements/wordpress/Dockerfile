FROM debian:bullseye

ARG WP_ADMIN_USER
ARG WP_ADMIN_PWD
ARG WP_ADMIN_EMAIL
ARG WP_USER
ARG WP_PWD
ARG WP_EMAIL


RUN apt-get update -y && apt-get upgrade -y && \
apt-get -y install php-fpm php-mysql php-zip curl wget && service php7.4-fpm start

COPY ./conf/wp-config.php /

COPY ./tools/wp-script.sh /

RUN chmod +x /wp-script.sh

CMD ["./wp-script.sh"]
