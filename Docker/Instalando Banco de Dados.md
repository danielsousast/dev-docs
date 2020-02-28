## Postgres
```sudo docker run --name postgress -e POSTGRES_PASSWORD=docker -d -p 5432:5432 postgres```


## MongoDB
```
docker pull tutum/mongodb
```

Criação de servidor sem senha, recomendado para ambiente de desenvolvimento:

```
docker run -d -p 27017:27017 -p 28017:28017 -e AUTH=no tutum/mongodb
```

Criação de servidor especificando uma senha:

```
docker run --name mongo -d -p 27017:27017 -p 28017:28017 -e MONGODB_PASS=docker tutum/mongodb
```

## Redis

```
docker pull redis
```

docker run --name redis -d -p 6379:6379 redis
