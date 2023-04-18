FROM docker.io/library/nextcloud:fpm
RUN apt update -y
RUN apt install smbclient libsmbclient-dev -y
RUN apt install cron -y
RUN apt install libmagickcore-6.q16-6-extra
RUN apt install ffmpeg
RUN apt install nano -y
RUN pecl install smbclient
RUN docker-php-ext-enable smbclient