FROM php:7.2.8-fpm
RUN apt-get update && apt-get install -y --no-install-recommends libicu-dev git mysql-client
WORKDIR /usr/src/php/ext
RUN git clone -b php7 --depth 1 https://github.com/Connehito/phpredis.git redis
RUN docker-php-ext-install pdo_mysql mysqli mbstring redis
WORKDIR /var/www
