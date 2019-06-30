FROM php:7.2-fpm-alpine3.9
RUN apk update && apk --no-cache --update-cache add vim \
   zip \
   unzip \
   iputils-ping \
   git
RUN docker-php-ext-install pdo_mysql
