FROM nginx:latest

LABEL maintainer="Nextpertise"

RUN mkdir -p /var/www/default/html/
COPY /src/www/index.php /var/www/default/html/
COPY src/config/default.conf /etc/nginx/conf.d/default.conf
