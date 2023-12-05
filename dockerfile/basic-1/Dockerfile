FROM php:8.1.0-apache

ARG IMPERIUM
ARG USER

ENV USER=${USER}
ENV IMPERIUM=${IMPERIUM}

COPY ./php-code/index.php /var/www/html
EXPOSE 80