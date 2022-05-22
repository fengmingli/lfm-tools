## repo
```shell
https://github.com/mongodb/mongo-tools
```

## download
```shell
https://www.mongodb.com/try/download/database-tools
```

## doc
```shell
https://www.mongodb.com/docs/v4.2/reference/program/mongodump/
```

## useage
```shell
排除指定的集合
mongodump  --db test --excludeCollection=users --excludeCollection=salaries
指定ip,端口，用户名，认证，压缩，输出目录
mongodump --host mongodb1.example.net --port 37017 --username user --password "pass" --gzip --out /opt/backup/mongodump-2019-04-17

mongorestore --collection people --db accounts dump/
mongorestore --host mongodb1.example.net --port 37017 --username user --password "pass" /opt/backup/mongodump-2019-04-17
mongorestore --gzip --archive=test.20150715.gz --db test
mongorestore --archive=test.20150715.archive --db test
```
