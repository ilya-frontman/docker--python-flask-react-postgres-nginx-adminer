# NODE-API-POSTGRES-NGINX-ADMINER (DOCKER)

### Source parts

* client/ use template [cra-ts-sass-tailwind-svg-sprite](https://github.com/ilya-frontman/cra-ts-sass-tailwind-svg-sprites.git)
* server/ use template [python-flask-postgres-starter](https://github.com/ilya-frontman/python-flask-postgres-starter)

### Development up

```
docker-compose up -d 
```
> uses standard docker-compose.yml and .env file

### Production up

```
docker-compose -f docker-compose.prod.yml --env-file .env.prod up
```
> uses prod docker-compose.prod.yml and .env.prod file
