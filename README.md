# ALMANAC Deployment
Contains docker compose files and default configuration files/examples

To get started do one of two things:

```bash
docker-compose -f docker-compose.mqtt.yml -p almanacproject up -d
```
or
```bash
docker network create almanacproject_backend
```
Both will create the network that is needed for all the other components - but the first command will also start the mosquitto broker.
