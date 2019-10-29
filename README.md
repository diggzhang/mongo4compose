# mongo4compose
MongoDB 4.0 Docker Compose

# How to run

```shell
docker-compose -f docker-compose-mongo4order.yml up -d
mongo --port 27018 --authenticationDatabase admin -u root -p Yangcong345
docker-compose -f docker-compose-mongo4order.yml down
```
