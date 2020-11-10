FROM nginx:1.17.9-alpine

WORKDIR /etc/nginx/
RUN mkdir /var/www
COPY nginx.conf /etc/nginx/nginx.conf
COPY index.html /var/www