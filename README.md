# FullStack-Kafka
![ci](https://user-images.githubusercontent.com/62883434/214236348-35bf4f99-3991-4f97-b39a-2b61fc7933c1.svg) ![68747470733a2f2f72656164746865646f63732e6f72672f70726f6a656374732f656c6b2d646f636b65722f62616467652f3f76657273696f6e3d6c6174657374](https://user-images.githubusercontent.com/62883434/214236419-98fb1081-30a7-4061-9a32-e865f198f26a.svg) ![badge (1)](https://user-images.githubusercontent.com/62883434/214236504-fdb68f82-dd76-4062-b55a-30ab32c58a36.svg) ![badge](https://user-images.githubusercontent.com/62883434/214236528-c8b781a8-3a2b-4a59-877e-d79c8e8e095f.svg)

# Apache Kafka packaged 
Apache Kafka is a distributed streaming platform designed to build real-time pipelines and can be used as a message broker or as a replacement for a log aggregation solution for big data applications.
What is event streaming?
Event streaming is the digital equivalent of the human body's central nervous system. It is the technological foundation for the 'always-on' world where businesses are increasingly software-defined and automated, and where the user of software is more software.

Technically speaking, event streaming is the practice of capturing data in real-time from event sources like databases, sensors, mobile devices, cloud services, and software applications in the form of streams of events; storing these event streams durably for later retrieval; manipulating, processing, and reacting to the event streams in real-time as well as retrospectively; and routing the event streams to different destination technologies as needed. Event streaming thus ensures a continuous flow and interpretation of data so that the right information is at the right place, at the right time.

![kafkalogooo](https://user-images.githubusercontent.com/62883434/221397765-34d445e9-f2bc-4942-962f-14de4efd27cd.png)

### Kafka APIs
###### In addition to command line tooling for management and administration tasks, Kafka has five core APIs for Java and Scala:

The Admin API to manage and inspect topics, brokers, and other Kafka objects.
The Producer API to publish (write) a stream of events to one or more Kafka topics.
The Consumer API to subscribe to (read) one or more topics and to process the stream of events produced to them.
The Kafka Streams API to implement stream processing applications and microservices. It provides higher-level functions to process event streams, including transformations, stateful operations like aggregations and joins, windowing, processing based on event-time, and more. Input is read from one or more topics in order to generate output to one or more topics, effectively transforming the input streams to output streams.
The Kafka Connect API to build and run reusable data import/export connectors that consume (read) or produce (write) streams of events from and to external systems and applications so they can integrate with Kafka. For example, a connector to a relational database like PostgreSQL might capture every change to a set of tables. However, in practice, you typically don't need to implement your own connectors because the Kafka community already provides hundreds of ready-to-use connectors.

![kafka-on-ubuntu-apache-kafka](https://user-images.githubusercontent.com/62883434/221397823-b2e3dc1c-5347-4d61-919f-f3515a7ea714.png)

### The packages available in this stack

##### 1- Kafka  ![WIDE - Black on Transparent](https://user-images.githubusercontent.com/62883434/221398495-585c1954-a9b5-4166-81bf-823d2f4a395d.png)


##### 2- Kafka-connect  ![connect](https://user-images.githubusercontent.com/62883434/221398441-d0f137b8-fb0a-4584-86e7-872cb8e38b26.png)


##### 3- Kafka-UI  ![default_49a504fbaa35a1b07b8f44abb9b90b8996f6068d](https://user-images.githubusercontent.com/62883434/221398458-a18c08d7-0b6a-4705-9515-7ba305c34f55.png)


##### 4- KsqlDB  ![ksqldb](https://user-images.githubusercontent.com/62883434/221398695-7f571493-2f86-4e94-9b9f-91cfcad895f3.png)


##### 5- Zookeeper


##### 6- Cassandra   ![cassandra](https://user-images.githubusercontent.com/62883434/221398533-4d046679-072c-4be5-bac2-885bcaaaf6a5.png)

##### 7- EMQX
