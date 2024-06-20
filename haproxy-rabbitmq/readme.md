# Usage
HAProxy for RabbitMQ. It is necessary to create dedicated network for RabbitMQ and HAProxy containers.

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
``` bash
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

## Test
Test of the haproxy.cfg configuration
```bash
make test
```

# Additional Information
For more information on haproxy and Docker, please refer to the official documentation: \
[HAProxy Documentation](https://docs.haproxy.org/) \
[Docker Documentation](https://docs.docker.com/) \
[Docker Compose Documentation](https://docs.docker.com/compose/)