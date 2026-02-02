FROM ubuntu
COPY index.html /var/www/html/index.html
RUN apt-get update && apt-get install -y apache2
ENTRYPOINT apachectl -D FOREGROUND