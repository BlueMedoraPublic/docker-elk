FROM elasticsearch:5-alpine 
ADD config/elasticsearch.yml /etc/elasticsearch/
ENV ES_JAVA_OPTS="-Des.path.conf=/etc/elasticsearch"

CMD ["-E", "discovery.zen.minimum_master_nodes=1"]
