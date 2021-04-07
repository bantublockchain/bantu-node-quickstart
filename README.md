### First time only:

```sh
docker-compose down
docker-compose pull
docker-compose up core-postgres
docker-compose run --rm core new-db > new-db.log
docker-compose stop core-postgres
docker-compose up expansion-postgres
docker-compose stop expansion-postgres

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

docker-compose logs -f core

docker-compose logs -f expansion

```