#### Start Zookeeper : `bin/zookeeper-server-start.sh config/zookeeper.properties`

#### Start Kafka Server : `bin/kafka-server-start.sh config/server.properties`

#### List Of Arguments For Topic : `bin/kafka-topics.sh` 

#### Create Kafka Topic Using Bootstrap Server :  `bin/kafka-topics.sh --create --bootstrap-server localhost:9092 --topic topicname`

#### Create Kafka Topic Using Zookeeper :  `bin/kafka-topics.sh --create --zookeeper localhost:2181 --topic topicname`

#### Get List Of Available Topics Using Bootstrap Server :  `bin/kafka-topics.sh --list --bootstrap-server localhost:9092 `

#### Get List Of Available Topics Using Zookeeper :  `bin/kafka-topics.sh --list --zookeeper localhost:2181 `

#### Get Topic Description Using Bootstrap Server :  `bin/kafka-topics.sh --describe --zookeeper localhost:2181 --topic topicname `

#### Get Topic Description Using Zookeeper :  `bin/kafka-topics.sh --describe --bootstrap-server localhost:9092 --topic topicname `

#### Send Message :  `bin/kafka-console-producer.sh --broker-list localhost:9092 --topic topicname `

#### Consume Message :  `bin/kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic topicname `

#### Consume Message From Beginning :  `bin/kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic topicname --from-beginning `
