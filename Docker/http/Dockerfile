FROM gns3-base:latest
RUN apk update
RUN apk add apache2 --no-cache
COPY start_http.sh /
RUN mkdir -p /run/apache2/
RUN sed -i 's/#ServerName www.example.com:80/ServerName www.example.com:80/g' /etc/apache2/httpd.conf
