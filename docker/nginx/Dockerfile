FROM nginx:latest

RUN apt update && apt install -y procps
COPY ./docker/nginx/nginx.conf /etc/nginx/nginx.conf
