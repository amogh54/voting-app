FROM ubuntu:latest

ADD default.conf /etc/nginx/conf.d/default.conf

RUN apt-get update && apt-get install nginx -y

CMD [ "nginx", "-g", "daemon off;"]

