FROM ubuntu:16.04
MAINTAINER Amar Krishna (amar266@gmail.com)
RUN apt-get update
RUN apt-get install -y apache2
RUN rm /var/www/html/index.html
COPY index.html /var/www/html
EXPOSE 80
CMD apachectl -D FOREGROUND
