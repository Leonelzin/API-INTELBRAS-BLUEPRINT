FROM nginx:1.21

ENV NGINX_PORT=8080

COPY ./default.conf.template /etc/nginx/templates/
COPY ./v4 /usr/share/nginx/html/v4

EXPOSE 8080
