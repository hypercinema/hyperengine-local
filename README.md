# HyperEngine Local

## Docker Compose

Start them all at once:

```bash
docker-compose up
```

Start a single instance detached.

```bash
docker-compose up -d zookeeper
docker-compose up -d kafka
docker-compose up -d kafka_ui
```

View the logs

```bash
docker logs kafks
```
