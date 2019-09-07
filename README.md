# docker-mysql

#### TL;DR

```
cp env.sample env
docker-compose up -d

docker ps
docker-compose ps

docker logs docker-mysql_db_1 
docker exec -it docker-mysql_db_1 bash
mysql -u root -psomething
mysql -u example -pexample

docker-compose down
```

#### Override

To persist data and override MySQL version, et cetera:

```
cp docker-compose.override.yaml.sample docker-compose.override.yaml
```

#### Access through [Adminer UI](https://www.adminer.org)

http://localhost:8181/?server=db

## REF

https://hub.docker.com/_/mysql
