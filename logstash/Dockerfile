FROM logstash:5-alpine
ADD config/logstash.conf /etc/logstash/conf.d/
# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-input-beats
