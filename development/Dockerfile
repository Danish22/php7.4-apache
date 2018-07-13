FROM jasonmccallister/php-apache:latest

ARG PECL_EXT="xdebug"

# change settings for php
COPY php.ini /usr/local/etc/php/conf.d

# install and enable xdebug
RUN pecl install $PECL_EXT && docker-php-ext-enable $PECL_EXT
