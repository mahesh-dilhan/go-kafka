### Kafka -Go

#### Start Zookeeper 

##### create a topic 
<---
kafka-topics --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic country
-->

#### Hot and Cold message can be differentiated using attribute 