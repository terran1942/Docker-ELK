# Docker ELK
Build ELK stack on the Docker

## Background
We usually need ELK for analysis of log, This project is tools of learning ELK, enjoy it!

Containers include:
+ Elasticsearch cluster, 3 nodes
+ Kibana 
+ Logstash 
+ Filebeat
+ Kafka cluster, 3 nodes

## Get started
This project uses [docker](https://docs.docker.com/install/) and [docker compose](https://docs.docker.com/compose/install/). 
Go check them out if you do not have them locally installed.

Create ELK containers command following:
``` shell
docker-compose build
docker-compose up -d
```

Stop ELK containers, command following:
``` shell
docker-compose stop
```

Start ELK containers, command following:
``` shell
docker-compose start
```

If you want to delete ELK on your machine，command following:
``` shell
docker-compose down
```

## Usage
+ Create log file in logs directory such as test.log.
+ Open **http://localhost:5601** in your browser, start using kibana to analysis log.

## Contributing

## License

MIT © Yongliang Li