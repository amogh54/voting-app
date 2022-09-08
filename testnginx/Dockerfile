FROM ubuntu:latest
#RUN rm -rfv /etc/nginx/conf.d/*
RUN apt-get update && apt-get install nginx -y

RUN apt-get install net-tools -y

RUN rm -rfv /etc/nginx/sites-available/*

ADD default /etc/nginx/sites-available/s

CMD [ "nginx", "-g", "daemon off;"]


