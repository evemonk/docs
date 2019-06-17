# Docker

## Pull all required images

```shell
# docker-compose pull
```

### Create database 

```shell
# docker-compose run --rm backend bundle exec rails db:create db:migrate
```


### Or restore from dump

```shell
# docker-compose up -d postgresql
# docker exec -i evemonk_postgresql createdb -U postgres evemonk_production
# docker exec -i evemonk_postgresql psql -U postgres evemonk_production < dump-2019-05-21.sql 
# docker-compose run --rm backend bundle exec rails db:migrate
# docker-compose run --rm backend bundle exec rails searchkick:reindex:all
# docker-compose up -d
```

```shell
# docker-compose run --rm backend bundle exec rails db:create db:migrate
```


docker-compose pull
