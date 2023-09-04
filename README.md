# inception

 # ngnix
  NGINX is open source software for web serving, reverse proxying, caching, load balancing, media streaming, and more. It started out as a web server designed for maximum performance and stability. In addition to its HTTP server capabilities, NGINX can also function as a proxy server for email (IMAP, POP3, and SMTP) and a reverse proxy and load balancer for HTTP, TCP, and UDP servers.
Backstory

Igor Sysoev originally wrote NGINX to solve the C10K problem, a term coined in 1999 to describe the difficulty that existing web servers experienced in handling large numbers (the 10K) of concurrent connections (the C). With its event‑driven, asynchronous architecture, NGINX revolutionized how servers operate in high‑performance contexts and became the fastest web server available.

NGINX as a Web Server

The goal behind NGINX was to create the fastest web server around, and maintaining that excellence is still a central goal of the project. NGINX consistently beats Apache and other servers in benchmarks measuring web server performance. Since the original release of NGINX, however, websites have expanded from simple HTML pages to dynamic, multifaceted content. NGINX has grown along with it and now supports all the components of the modern Web, including WebSocket, HTTP/2, gRPC, and streaming of multiple video formats (HDS, HLS, RTMP, and others).

Though NGINX became famous as the fastest web server, the scalable underlying architecture has proved ideal for many web tasks beyond serving content. Because it can handle a high volume of connections, NGINX is commonly used as a reverse proxy and load balancer to manage incoming traffic and distribute it to slower upstream servers – anything from legacy database servers to microservices.

NGINX also is frequently placed between clients and a second web server, to serve as an SSL/TLS terminator or web accelerator. Acting as an intermediary, NGINX efficiently handles tasks that might slow down your web server, such as negotiating SSL/TLS or compressing and caching content to improve performance. Dynamic sites, built using anything from Node.js to PHP, commonly deploy NGINX as a content cache and reverse proxy to reduce load on application servers and make the most effective use of the underlying hardware.

# MariaDB 

MariaDB Server is a general purpose open source relational database management system. It’s one of the most popular database servers in the world, with notable users including Wikipedia, WordPress.com and Google. MariaDB Server is released under the GPLv2 open source licence and is guaranteed to remain open source.

It can be used for high-availability transaction data, analytics, as an embedded server, and a wide range of tooling and applications support MariaDB Server.

History

When MariaDB Server’s predecessor, MySQL, was bought by Oracle in 2009, MySQL founder Michael “Monty” Widenius forked the project due to concerns about Oracle’s stewardship, naming the new project MariaDB. MySQL was named after his first daughter, My, while MariaDB is named after his second daughter, Maria.

Most of the original developers joined the new project and MariaDB Server has continued to develop rapidly since then. 
 
https://yaml.org/spec/1.2.2/
