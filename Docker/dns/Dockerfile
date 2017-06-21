FROM gns3-base:latest
RUN apk update
RUN apk add bind --no-cache
COPY named.conf /etc/bind/
COPY noface.com.br.zone /etc/bind/
COPY start_dns.sh /
RUN mkdir -p /var/log/named/
