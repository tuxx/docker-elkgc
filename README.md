# docker-elkgc
Docker-compose [Elasticsearch](https://www.elastic.co/), [Logstash](https://www.elastic.co/products/logstash), [Kibana](https://www.elastic.co/products/kibana), [Grafana](https://grafana.com/) and [Cerebro](https://github.com/lmenezes/cerebro)

This docker-compose file has persistent data for all the containers except cerebro

# How to run

```bash
docker-compose up -d
```

# How to stop
```bash
docker-compose down # (optional cleanup: --rmi all -v)
```

# What to reach

## Web interfaces
- Grafana at http://localhost:3000
- Kibana at http://localhost:5601
- Cerebro at http://localhost:9000

## API
- Logstash at http://localhost:5000/6000
- Elasticsearch at http://localhost:9200/9300
