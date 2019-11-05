FROM ubuntu:16.04
MAINTAINER Amar Krishna (amar266@gmail.com)
RUN apt-get update
RUN apt-get install -y apache2
COPY index.html /var/ww/html
EXPOSE 80
CMD apachectl -D FOREGROUND
