#https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash-oss:6.2.4

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-input-rss
RUN logstash-plugin install logstash-input-twitter
RUN logstash-plugin install logstash-filter-rest

#RUN logstash-plugin install x-pack
