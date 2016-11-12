graylog docker compose
=======================

from https://hub.docker.com/r/graylog2/server/

## Config

```
mkdir config
cd config
wget https://raw.githubusercontent.com/Graylog2/graylog2-images/2.1/docker/config/graylog.conf
wget https://raw.githubusercontent.com/Graylog2/graylog2-images/2.1/docker/config/log4j2.xml
```

## Run
```
docker-compose up
```

## Test
 - http://127.0.0.1:9000
 - login with admin/admin
