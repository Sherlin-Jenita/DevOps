FROM ubuntu:latest

RUN apt-get -y update

RUN apt-get install -y apache2 curl

EXPO 80

WORKDIR /var/www/html

COPY index.html /var/www/html/index.html

ENTRYPOINT ["/user/sbin/apache2ctl"]

CMD ["-D", "FOREGROUND" ]
