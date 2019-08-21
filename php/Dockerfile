FROM    php:7.2-cli

RUN     docker-php-ext-install pdo_mysql \
        && mkdir -p /usr/src/app/

CMD     php -S 0.0.0.0:80 -t /usr/src/app/