# VNLab Training - EFK Stack
### Environments
Make an environment file `.env` with the content below:
```env
ELASTIC_PASSWORD=<your_elastic_password>
KIBANA_PASSWORD=<your_kibana_password>
```

### Docker Compose
Run Docker Compose Daemon:
```
docker compose up -d
```
When everything is finished, you can 'seed' some log data into Elasticsearch by requesting into httpd service:
```
curl 127.0.0.1
```
Test Elasticsearch and Kibana Web Interface at the following URL:
### Elasticsearch
`127.0.0.1:9200/_search`
### Kibana
`127.0.0.1:5601`
