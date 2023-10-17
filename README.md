# inception

 # ngnix
  NGINX is open source software for web serving, reverse proxying, caching, load balancing, media streaming, and more. It started out as a web server designed for maximum performance and stability. In addition to its HTTP server capabilities, NGINX can also function as a proxy server for email (IMAP, POP3, and SMTP) and a reverse proxy and load balancer for HTTP, TCP, and UDP servers.

NGINX as a Web Server

NGINX supports all the components of the modern Web, including WebSocket, HTTP/2, gRPC, and streaming of multiple video formats (HDS, HLS, RTMP, and others).

Though NGINX became famous as the fastest web server, the scalable underlying architecture has proved ideal for many web tasks beyond serving content. Because it can handle a high volume of connections, NGINX is commonly used as a reverse proxy and load balancer to manage incoming traffic and distribute it to slower upstream servers – anything from legacy database servers to microservices.

NGINX also is frequently placed between clients and a second web server, to serve as an SSL/TLS terminator or web accelerator. Acting as an intermediary, NGINX efficiently handles tasks that might slow down your web server, such as negotiating SSL/TLS or compressing and caching content to improve performance. Dynamic sites, built using anything from Node.js to PHP, commonly deploy NGINX as a content cache and reverse proxy to reduce load on application servers and make the most effective use of the underlying hardware.

# MariaDB 

MariaDB Server is a general purpose open source relational database management system. It’s one of the most popular database servers in the world, with notable users including Wikipedia, WordPress.com and Google. MariaDB Server is released under the GPLv2 open source licence and is guaranteed to remain open source.

It can be used for high-availability transaction data, analytics, as an embedded server, and a wide range of tooling and applications support MariaDB Server.

# adding a .env file

Add the .env file to the srcs folder

/srcs:
total XX
drwxrwxr-x 3 wil wil 4096 avril 42 20:42 .
drwxrwxr-x 3 wil wil 4096 avril 42 20:42 ..
-rw-rw-r-- 1 wil wil XXXX avril 42 20:42 docker-compose.yml
-rw-rw-r-- 1 wil wil XXXX avril 42 20:42 .env
drwxrwxr-x 5 wil wil 4096 avril 42 20:42 requirements

env file

DB_NAME=wordpress

DB_USER=usr 

DB_USER_PASS=upass

DB_ROOT=root

WP_ADMIN_USER=mk

WP_ADMIN_PWD=adpass

WP_ADMIN_EMAIL= \<admin-email\>

WP_USER=wp_usr

WP_PWD=wp_upass

WP_EMAIL= \<wp-email\>


CERT_PATH=/etc/ssl/certs

KEY_PATH=/etc/ssl/private
