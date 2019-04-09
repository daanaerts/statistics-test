FROM docker.elastic.co/logstash/logstash:6.7.0@sha256:e8023ea54fcf94e6a3356c8c80e362f4c2a6b48d3871e55aa5cbe6bacec591fe

COPY mysql-connector-java-8.0.15.jar /usr/share/logstash
COPY logstash-input.conf /usr/share/logstash
RUN bin/logstash-plugin install logstash-input-jdbc