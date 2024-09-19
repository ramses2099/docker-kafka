# docker-kafka
Project docker compose kafka

# container node kafka
```
docker exec -it kafka /bin/bash
```

# go to directory of kafka
```
cd /opt/kafka_2.13-2.8.1/bin/
```

# create topic
```
kafka-topics.sh --create --topic test --zookeeper zookeeper:2181 --partitions 1 --replication-factor 1
```

# create data for the topic
```
kafka-console-producer.sh --topic test --bootstrap-server localhost:9092
```
