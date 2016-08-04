# docker-influxdb-alpine
Influxdb Alpine Docker File

# Usage
```
$ docker run -p 8083:8083 -p 8086:8086 -v <docker_volume_name>:/var/lib/influxdb uretgec/influxdb-alpine
```

# Options
- 8086 HTTP API port
- 8083 Administrator interface port

# Many many Thanks
- https://github.com/influxdata/influxdata-docker
