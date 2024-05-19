FROM php:8.3-apache

# Install system dependencies
RUN apt-get update && apt-get install -y git \
    && docker-php-ext-install mysqli \
    && pecl install xdebug-3.3.2 \
    && docker-php-ext-enable xdebug
