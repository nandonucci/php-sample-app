# PHP image
FROM php:7.2-apache

# isntall MYSQLI extension
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli

# root directory
WORKDIR /var/www/html/

# copy ROOT to VAR/WWW/HTML
COPY . .