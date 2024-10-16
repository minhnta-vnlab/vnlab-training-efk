FROM elasticsearch:8.15.2

# Disable SSL Security
RUN echo "xpack.security.enabled: false" >> /usr/share/elasticsearch/config/elasticsearch.yml

EXPOSE 9200

CMD ["elasticsearch"]