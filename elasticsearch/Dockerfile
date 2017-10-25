FROM elasticsearch:2.3.5

RUN bin/plugin install mobz/elasticsearch-head

COPY config /usr/share/elasticsearch/config

EXPOSE 9300

CMD  ["bin/elasticsearch", "-Des.insecure.allow.root=true"]
