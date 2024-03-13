Zookeeper Configuration to start zookeeper server: **zkserver**

Kafka Broker server Startup :**.\bin\windows\kafka-server-start.bat .\config\server.properties**

Files to Edit :
 Set **ZOOKEEPER_HOME**=zookeper directory path as System Variable

 JAVA_HOME path should be setup to JDK location with **JDK 8+**

 Edit kafka/config/**server.properties** changing *log.dirs*=/tmp/kafka-logs” to “log.dir= C:\kafka_2.11-0.9.0.0\kafka-logs.

 Edit **zookeeper.config** with *dataDir*=/tmp/zookeeper to :\zookeeper-3.4.7\data
