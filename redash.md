- rename *docker-compose.product.yml* to **docker-compose.yml**
- postgres data volume setting

```
$ docker-compose up -d postgres redis
$ docker-compose run --rm server create_db
$ docker-compose up -d server worker nginx
$ docker-compose up -d
```
