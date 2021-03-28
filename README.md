# docker-smallbiz-stack

This project aims to provide a docker-based Stack of several useful software for a small SME server:

- a web server with PHP, MySQL and automatic SSL via Letsencrypt (via docker-letsencrypt-nginx-proxy-companion) / main domain name ;
- an elasticsearch server companion to the web server / only accessible via the first docker ;
- a database manager (Phpmyadmin) (subdomain db-manager) ;
- a backup tool for the whole to a cloud (subdomain backup-manager) ;
- a file server based on Seafile (subdomain files) ;
- a chat server based on rocket.chat (subdomain chat) ;
- a calendar and contact server based on Radicale 3.0 (subdomain calendar).
