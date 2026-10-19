# Kafka Cluster Infrastructure

Original local Kafka lab using KRaft mode (no ZooKeeper). It exposes Kafka only to the Docker
network, making it suitable for local producer/consumer experiments.

```bash
docker compose up -d
docker compose exec kafka kafka-topics --bootstrap-server kafka:9092 --create --topic events
```
Kafka cluster infrastructure and operational runbooks.
