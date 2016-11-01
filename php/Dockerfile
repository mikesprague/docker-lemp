FROM php:7.0-fpm

RUN docker-php-ext-install pdo_mysql

RUN curl -sS https://getcomposer.org/installer | php
RUN mv composer.phar /usr/local/bin/composer
