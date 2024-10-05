FROM php:8.3-fpm

# 作成した設定ファイルをコンテナ内にコピー
COPY ./php.ini /usr/local/etc/php/php.ini

RUN docker-php-ext-install pdo pdo_mysql

WORKDIR /var/www/html