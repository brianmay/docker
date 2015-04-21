FROM debian:jessie
MAINTAINER Brian May <brian@microcomaustralia.com.au>

RUN apt-get update && \
    apt-get install -y postgresql && \
    apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

VOLUME ["/etc/postgresql", "var/lib/postgresql"]
