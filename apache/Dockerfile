FROM debian:latest
RUN apt update && apt install -y apache2 php libapache2-mod-php

ENTRYPOINT [ "apachectl" , "-D" , "FOREGROUND" ]