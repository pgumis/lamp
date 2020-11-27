FROM php:7.4-cli
RUN apt-get -y update; \
    apt-get -y upgrade;
RUN docker-php-ext-install mysqli
COPY php.ini /usr/local/etc/php/php.ini
