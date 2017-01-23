# Docker Compose

## Build the images
```bash
docker-compose build
```

## Run the containers
```bash
docker-compose up
```

## To use the app container
```bash
docker exec -it counterapp_web_2 /bin/bash
```

## To use the mongodb server
```bash
docker exec -it counterapp_db_2 mongo
```

## Run tests
```bash
docker exec -it counterapp_web_2 python tests.py
```

## Start or stop containers
```bash
docker-compose start
docker-compose stop
```

## Remove the containers
```bash
docker-compose rm -v
```

## Start a container as background
```bash
docker-compose up -d db
```

## Run a container to debug
```bash
docker-compose run --service-ports web
```
