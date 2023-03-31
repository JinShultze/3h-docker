# ps: docker-compose up

## http

* <http://localhost:9870>  hadoop
* <http://localhost:16010>  hbase
* <http://localhost:8088>  hadoop

## 启动容器后

进入hbase容器，执行/opt/hbase-1.2.6/bin/hbase-daemon.sh start thrift 连接python

## hive创建外部表

hive通过建立外部表和hbase数据库产生映射关系
![external_table.png](external_table.png "创建外部表，hive连接hbase")
