FROM ubuntu:16.04

MAINTAINER TeamCloudYuga <ved@cloudyuga.guru>

RUN apt-get update -yq && \
    apt-get -yq install nginx && \
    apt-get -yq clean

ADD nginx.conf /etc/nginx/nginx.conf

ADD static /site

CMD ["nginx", "-g", "daemon off;"]

EXPOSE 80

VOLUME /sockets