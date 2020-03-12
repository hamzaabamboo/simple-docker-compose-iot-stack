# Simple IoT Stack environment

docker-compose powered iot stack environment of IoT applications.

## Tools Included
- node-red (server) Port :1880
- mosquitto (mqtt broker) Port :1883
- influxdb (database) Port :8086
- chronograf (database dashboard) Port :8087

## Running
```
$ docker-compose up
```

## Things considered important to do
- Setting up reverse proxy
- Setting up authentication

## FAQ

- Connecting chronograf ? use http://influxdb:8086
