# FullStack-Kafka
![ci](https://user-images.githubusercontent.com/62883434/214236348-35bf4f99-3991-4f97-b39a-2b61fc7933c1.svg) ![68747470733a2f2f72656164746865646f63732e6f72672f70726f6a656374732f656c6b2d646f636b65722f62616467652f3f76657273696f6e3d6c6174657374](https://user-images.githubusercontent.com/62883434/214236419-98fb1081-30a7-4061-9a32-e865f198f26a.svg) ![badge (1)](https://user-images.githubusercontent.com/62883434/214236504-fdb68f82-dd76-4062-b55a-30ab32c58a36.svg) ![badge](https://user-images.githubusercontent.com/62883434/214236528-c8b781a8-3a2b-4a59-877e-d79c8e8e095f.svg)

# Apache Kafka packaged 
Apache Kafka is a distributed streaming platform designed to build real-time pipelines and can be used as a message broker or as a replacement for a log aggregation solution for big data applications.
What is event streaming?
Event streaming is the digital equivalent of the human body's central nervous system. It is the technological foundation for the 'always-on' world where businesses are increasingly software-defined and automated, and where the user of software is more software.

Technically speaking, event streaming is the practice of capturing data in real-time from event sources like databases, sensors, mobile devices, cloud services, and software applications in the form of streams of events; storing these event streams durably for later retrieval; manipulating, processing, and reacting to the event streams in real-time as well as retrospectively; and routing the event streams to different destination technologies as needed. Event streaming thus ensures a continuous flow and interpretation of data so that the right information is at the right place, at the right time.

### Full stack Kafka, Contain  'Kafka - Kafka-connect - Kafka-UI - KsqlDB - Zookeeper - Cassandra - EMQX'
![kafkalogo](https://user-images.githubusercontent.com/62883434/214238951-c51fdfe8-76be-458f-9544-5037c756aef1.jpg)

### Kafka APIs
###### In addition to command line tooling for management and administration tasks, Kafka has five core APIs for Java and Scala:

The Admin API to manage and inspect topics, brokers, and other Kafka objects.
The Producer API to publish (write) a stream of events to one or more Kafka topics.
The Consumer API to subscribe to (read) one or more topics and to process the stream of events produced to them.
The Kafka Streams API to implement stream processing applications and microservices. It provides higher-level functions to process event streams, including transformations, stateful operations like aggregations and joins, windowing, processing based on event-time, and more. Input is read from one or more topics in order to generate output to one or more topics, effectively transforming the input streams to output streams.
The Kafka Connect API to build and run reusable data import/export connectors that consume (read) or produce (write) streams of events from and to external systems and applications so they can integrate with Kafka. For example, a connector to a relational database like PostgreSQL might capture every change to a set of tables. However, in practice, you typically don't need to implement your own connectors because the Kafka community already provides hundreds of ready-to-use connectors.
