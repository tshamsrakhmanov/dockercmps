command to run to create topic:
```bash
docker exec -it kafka1 kafka-topics --bootstrap-server localhost:9092 --create --topic test-topic --partitions 3 --replication-factor 3
```
