FROM php:7.4-fpm

RUN apt-get update

run  docker-php-ext-install mysqli && docker-php-ext-enable mysqli
WORKDIR /var/www
