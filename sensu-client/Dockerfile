FROM terjesannum/sensu-base:2
LABEL maintainer "terje@offpiste.org"

EXPOSE 3030

ENV LOG_LEVEL=info

COPY rabbitmq.json random.json /etc/sensu/conf.d/

COPY run.sh /opt/
CMD ["/opt/run.sh"]
