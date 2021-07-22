FROM php:7.4-apache
RUN apt-get update
RUN apt-get install -y libzip-dev libpng-dev libfreetype6-dev libjpeg62-turbo-dev
RUN docker-php-ext-configure gd --with-freetype=/usr/include --with-jpeg=/usr/include 
RUN docker-php-ext-install gd mysqli pdo_mysql 

