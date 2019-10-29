# mongo4compose
MongoDB 4.0 Docker Compose

# How to run

if you run docker with `root` user create `data` folder:

```
sh ./init
```

kick start:

```shell
docker-compose -f docker-compose-mongo4order.yml up -d
```

how to access with `mongo`:

```
mongo --port 27018 --authenticationDatabase admin -u root -p Yangcong345
```

remove:

```
docker-compose -f docker-compose-mongo4order.yml down
```
