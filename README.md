### First time only:

```sh
docker-compose pull
docker-compose up core-postgres
docker-compose run --rm core new-db > new-db.log
docker-compose stop core-postgres
```

### Subsequent runs:

```sh

docker-compose up

```


### Run detached on a remote server

```sh

docker-compose up -d

```

### Logs

```sh

docker-compose logs -f 

```