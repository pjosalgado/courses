FROM ubuntu:24.10

RUN apt-get update && apt-get install -y apache2

ADD app/ /var/www/html

EXPOSE 80

CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
