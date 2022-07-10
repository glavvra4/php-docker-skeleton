FROM php:7.4-php

RUN apt-get update && apt-get install -y curl

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

USER www-data:www-data

WORKDIR /app

CMD ["php-fpm"]
