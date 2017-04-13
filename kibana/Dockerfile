FROM kibana:5
ADD config/kibana.yml /etc/kibana/
RUN kibana-plugin install https://github.com/sivasamyk/logtrail/releases/download/0.1.11/logtrail-5.3.0-0.1.11.zip
