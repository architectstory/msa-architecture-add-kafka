# kafka server install and start

version : kafka_2.12-1.1.0
download url : https://kafka.apache.org/downloads

start: 
  1. zookeeper : sh kafka_2.12-1.1.0/bin/zookeeper-server-start.sh kafka_2.12-1.1.0/config/zookeeper.properties
  2. kafka : sh kafka_2.12-1.1.0/bin/kafka-server-start.sh kafka_2.12-1.1.0/config/server.properties
