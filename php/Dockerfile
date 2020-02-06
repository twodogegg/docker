FROM php:7.1-fpm

RUN docker-php-ext-install pdo pdo_mysql 

# RUN pecl install redis-4.0.1 \
#     && pecl install xdebug-2.8.1 \
#     && docker-php-ext-enable redis xdebug

# Use the default production configuration
RUN mv "$PHP_INI_DIR/php.ini-production" "$PHP_INI_DIR/php.ini"
