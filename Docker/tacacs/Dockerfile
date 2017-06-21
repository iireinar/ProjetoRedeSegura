FROM gns3/ubuntu:xenial
RUN apt-get -y update
RUN apt-get -y install tacacs+
COPY tac_plus.acct /etc/tacacs+/tac_plus.conf
COPY start_tac_plus.sh /start_tac_plus.sh
RUN touch /var/log/tac_plus.acct
