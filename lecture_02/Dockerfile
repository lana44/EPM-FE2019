FROM ubuntu

RUN apt-get -y update

RUN apt-get -y install nginx

CMD /usr/sbin/nginx -g "daemon off;"

COPY html /var/www/html/

COPY gitlearn1.jpg /var/www/html/

COPY gitlearn2.jpg /var/www/html/

EXPOSE 80