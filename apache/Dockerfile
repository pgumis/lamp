FROM httpd:2.4
RUN apt-get -y update; \
    apt-get -y upgrade;
COPY ./apache.conf /usr/local/apache2/conf/httpd.conf
EXPOSE 6666

