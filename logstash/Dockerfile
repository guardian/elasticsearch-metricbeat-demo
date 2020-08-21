ARG LOGSTASH_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${LOGSTASH_VERSION}

RUN logstash-plugin install logstash-output-kinesis
RUN logstash-plugin install logstash-output-stdout
