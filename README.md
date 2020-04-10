# Postgresql docker with Postgis installation and extensions

Based on:
```
http://fuzzytolerance.info/blog/2018/12/04/Postgres-PostGIS-in-Docker-for-production/
```

Start the container:
```shell
docker-compose up
```

Start the container in the background:
```shell
docker-compose up -d
```

Connect to the container:
```shell
docker exec -it postgres11-postgis3.0 bash
```

Connect to postgresql (when in container):
```shell
psql -U postgres
```

Show the tables (when connected to Postgresql):
```shell
\l
```

See the running docker processes:
```shell
docker ps
```

See the stopped containers:
```shell
docker ps -a | grep Exit
```

Remove a container:
```shell
docker rm CONTAINER-ID
```

See the exissting images:
```shell
docker images
```

Remove an image:
```shell
docker rmi IMAGE-ID
```
