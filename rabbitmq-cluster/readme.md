# Usage
RabbitMQ 3 node cluster.

# Steps to Run

## Create network
```bash
docker network create rabbitmq_network
```
## Run container
```bash
make up
```

# Commands
## Start
```bash
make up
```

## Stop
```bash
make down
```

## Logs from containers
```bash
make logs
```

## Remove data and temp files
```bash
make clear
```

# Logging
All logs are directed to /std/out.

# Additional Information
For more information on haproxy and Docker, please refer to the official documentation: \
[RabbitMQ Documentation](https://www.rabbitmq.com/docs) \
[Docker Documentation](https://docs.docker.com/) \
[Docker Compose Documentation](https://docs.docker.com/compose/)