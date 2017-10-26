# symfony-compose

A lightweight docker-compose file for Symfony app.

Services:
 - backend (php-cli with composer for development)
 - fpm (php-fpm with same extensions as backend, w/o composer)
 - nginx
 - sql (mariadb)

Extra installed extensions for php:
 - gd
 - intl
 - opcache
