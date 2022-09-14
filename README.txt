To start zookeeper

zookeeper-server-start.bat *path to your zookeeper.properties file* 
To start kafka server 
kafka-server-start.bat path to your server.properties file* 

To create kafka topic
kafka-topics.bat --create --topic spring-kafka --bootstrap-server localhost:9092 --replication-factor 1 --partitions 1

To consume kafka message 
kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic spring-kafka

