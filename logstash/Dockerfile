FROM logstash:5.6.8-alpine

COPY ./logstash/logstash.conf /usr/share/logstash/config

CMD ["-f", "/usr/share/logstash/config/logstash.conf"]