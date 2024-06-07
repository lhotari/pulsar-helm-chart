FROM apachepulsar/pulsar-all:3.3.0
USER 0
RUN apk add --no-cache bind-tools
COPY pulsar-zookeeper-ruok.sh /pulsar/bin/
USER 10000