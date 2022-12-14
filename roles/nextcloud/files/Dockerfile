FROM docker.io/library/nextcloud:fpm
RUN apt update -y
RUN apt install smbclient libsmbclient-dev -y
RUN apt install cron -y
RUN apt install nano -y
RUN pecl install smbclient