FROM gns3-dns:latest
COPY named.conf /etc/bind/
COPY noface.com.br.zone /etc/bind/
COPY start_dns.sh /
RUN mkdir -p /var/log/named/
