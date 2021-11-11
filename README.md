# Elastic Stack Docker

[![Validation](https://github.com/seanghay/elastic-stack-docker/actions/workflows/ci.yml/badge.svg)](https://github.com/seanghay/elastic-stack-docker/actions/workflows/ci.yml)

#### Start Elasticsearch & Kibana

```sh
docker-compose up -d
```

- Kibana: `http://127.0.0.1:5601`
- Elasticsearch: `http://127.0.0.1:9200`


#### Stop

```sh
docker-compose down
```

#### Stop & Remove Volumes

```sh
docker-compose down -v
```
