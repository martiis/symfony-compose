# symfony-compose

A lightweight docker-compose file for Symfony app.

### Services:
 - backend (php-cli with composer for development)
 - fpm (php-fpm with same extensions as backend, w/o composer)
 - nginx
 - sql (mariadb)

### Extra installed extensions for php:
 - gd
 - intl
 - opcache

### How to start:
`rm -fr ./code && symfony new code && docker-compose up`


Server runs on `127.0.0.1:8000`. To access container for development run `docker-compose run backend sh`
