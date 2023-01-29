FROM ubuntu

RUN apt-get update -y
RUN DEBIAN_FRONTEND=noninteractive apt-get install -y tzdata
#Instalamos PHP y 7ZIP
RUN apt-get update -y && apt-get install apache2 php curl libapache2-mod-php -y && rm -rf /var/lib/apt/lists/*

WORKDIR /var/www/html

COPY ./my-httpd.conf /etc/apache2/apache2.conf

RUN curl -O https://gist.githubusercontent.com/galcober/1825545/raw/3521b89f6620ea2361d528fb7cbd318889177a34/holamundo.php

EXPOSE 80

CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
