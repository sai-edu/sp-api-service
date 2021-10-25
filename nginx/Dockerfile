FROM nginx:1.19

RUN mkdir -p /opt/app/public

COPY config/default.conf /etc/nginx/conf.d/default.conf
COPY public/index.php /opt/app/public/index.php
