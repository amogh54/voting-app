FROM ubuntu:latest
#RUN rm -rfv /etc/nginx/conf.d/*
RUN apt-get update && apt-get install nginx -y

RUN apt-get install net-tools -y

#RUN rm -rfv /etc/nginx/sites-enabled/*

ADD default /etc/nginx/sites-enabled/

CMD [ "nginx", "-g", "daemon off;"]
