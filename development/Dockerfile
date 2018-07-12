FROM jasonmccallister/php-apache:latest

ARG PECL_EXT="xdebug"

# install and enable xdebug
RUN pecl install $PECL_EXT && docker-php-ext-enable $PECL_EXT
