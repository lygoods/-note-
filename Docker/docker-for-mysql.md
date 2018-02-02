# mysql installation
```
docker pull mysql
```

```
docker run -d --name=mysql -e MYSQL_ROOT_PASSWORD=11 -v /database/mysql:/var/lib/mysql mysql
```
-v local_database_address: docker_mysql_database_address

Enter in docker container

```
docker exec -it mysql bash
```
```
root@49c1d4318746:/# su mysql
$ mysql -u root -p
```