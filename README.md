# Awesome Kafka

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome articles, tutorials, courses, and resources for the Apache Kafka ecosystem.

![20201021_Introduction-to-Apache-Kafka_BLOG-FEATURED-IMAGE](https://user-images.githubusercontent.com/13417552/122371020-2bf0e000-cf7d-11eb-9627-07833cf0d9c2.jpg)


## Contributing

Contributions are very welcome!

- Fork the repo
- Star the repo
- Raise Pull Request to branch 'main'
- Make sure to check for duplicacy before raising pull request.

Thank you!

Table of Contents
=================
  * [Articles](#articles)
  * [UI / Cluster management](#ui--cluster-management)
  * [Configurations](#configurations)
  * [Clients](#clients)
  * [CLI / Tools](#cli--tools)
  * [Schema](#schema)
  * [Security](#security)
  * [Testing](#testing)
  * [Talks / Presentations](#talks--presentations)
  * [Books](#books)



## Articles

   * [Introduction to Kafka](http://sysadvent.blogspot.com.br/2014/12/day-4-introduction-to-kafka.html)
   * [All Kafka tutorials by Confluent](https://kafka-tutorials.confluent.io/)
   * [Apache Kafka, Samza, and the Unix Philosophy of Distributed Data](http://www.confluent.io/blog/apache-kafka-samza-and-the-unix-philosophy-of-distributed-data)
   * [Event Sourcing: What it is and why it's awesome](https://dev.to/barryosull/event-sourcing-what-it-is-and-why-its-awesome)
   * [Introducing Kafka Streams: Stream Processing Made Simple](http://www.confluent.io/blog/introducing-kafka-streams-stream-processing-made-simple)
   * [SSL Authentication with Apache Kafka](https://medium.com/contino-engineering/ssl-authentication-with-apache-kafka-e8285bfe90a5)
   * [Kafka Cheet Sheet](https://github.com/Landoop/kafka-cheat-sheet)
   * [Apache Kafka for Beginners](http://blog.cloudera.com/blog/2014/09/apache-kafka-for-beginners/)
   * [Introduction to Stream Processing using Kafka Streams](https://www.loginradius.com/engineering/blog/stream-processing-using-kafka/)
   * [Understanding Kafka with Factorio](https://hackernoon.com/understanding-kafka-with-factorio-74e8fc9bf181)
   * [Using logs to build a solid data infrastructure (or: why dual writes are a bad idea)](http://www.confluent.io/blog/using-logs-to-build-a-solid-data-infrastructure-or-why-dual-writes-are-a-bad-idea/)
   * [Bottled Water: Real-time integration of PostgreSQL and Kafka](http://www.confluent.io/blog/bottled-water-real-time-integration-of-postgresql-and-kafka/)
   * [Deploying Apache Kafka on AWS Elastic Block Store (EBS)](http://www.confluent.io/blog/deploying-apache-kafka-on-aws-elastic-block-store-ebs)
   * [How We Monitor and Run Kafka At Scale](http://www.confluent.io/blog/how-we-monitor-and-run-kafka-at-scale-signalfx)
   * [Monitoring Kafka performance metrics](https://www.datadoghq.com/blog/monitoring-kafka-performance-metrics/)
   * [Kafka for uSwitch's Event Pipeline](http://oobaloo.co.uk/kafka-for-uswitchs-event-pipeline)
   * [Next Gen Real-time Streaming with Storm-Kafka Integration](http://blog.infochimps.com/2012/10/30/next-gen-real-time-streaming-storm-kafka-integration/)
   * [All netflix tech blog kafka tagged articles](http://techblog.netflix.com/search/label/kafka)
   * [All linked in tech blog kafka tagged articles](https://engineering.linkedin.com/blog/topic/kafka)
   * [How to use Apache Kafka to transform a batch pipeline into a real-time one](https://medium.com/@stephane.maarek/how-to-use-apache-kafka-to-transform-a-batch-pipeline-into-a-real-time-one-831b48a6ad85)
   * [Maven quick start for Kafka Connect connectors](https://github.com/jcustenborder/kafka-connect-archtype)
   * [Kafka Listeners - Explained](https://rmoff.net/2018/08/02/kafka-listeners-explained/)

## UI / Cluster management  
 
   * [Kafdrop - Kafdrop is a web UI for viewing Kafka topics and browsing consumer groups. The tool displays information such as brokers, topics, partitions, consumers, and lets you view messages.](https://github.com/obsidiandynamics/kafdrop)
   * [Kafka Eagle - A easy and high-performance monitoring system, as well as offsets or metadata and other kafka information. ](https://www.kafka-eagle.org/)
   * [Klustr - Monitoring tool and graphic visualizer for Apache Kafka that helps you track key metrics about your cluster in real-time.](https://github.com/oslabs-beta/klustr)
   * [Remora - Kafka consumer lag-checking application for monitoring, written in Scala and Akka HTTP; a wrap around the Kafka consumer group command.Integrations with Cloudwatch and Datadog.Authentication recently added.](https://github.com/zalando-incubator/remora)
   * [Kowl  - Kowl is a modern Kafka Web UI for exploring Kafka messages, configurations and more with a focus on a good UI/UX. Written in Go & React.](https://github.com/cloudhut/kowl)
   * [AKHQ  - Kafka GUI for Apache Kafka to manage topics, topics data, consumers group, schema registry, connect and more.](https://github.com/tchiotludo/akhq)

## Configurations  
 
   * [kafka-gitops - Manage Apache Kafka topics and generate ACLs through a desired state file.](https://github.com/devshawn/kafka-gitops)
   * [Kafka Specs - Tool to ease and automate Apache Kafka cluster configuration management.](https://github.com/streamthoughts/kafka-specs)
   * [kattlo - Kattlo gives a way to manage topics, ACLs, users, schemas, ksqlDB, employing a evolutionary configuration. Easy to understand, easy to write and easy to apply.](https://kattlo.github.io/)
   * [Julie - An operational manager for Apache Kafka (Automation, GitOps, SelfService)](https://github.com/kafka-ops/julie)

## Clients  
 
   * [kafkajs - A modern Apache Kafka client for node.js](https://kafka.js.org/)
   * [Kafka Rust - Rust client for Apache Kafka.](https://github.com/kafka-rust/kafka-rust)
   * [librdkafka - The Apache Kafka C/C++ library.](https://github.com/edenhill/librdkafka)
   * [Franz-go - franz-go is a feature complete client written in native Go.)](https://github.com/twmb/franz-go)

## CLI / Tools 

   * [Kafkacat - Generic command line non-JVM Apache Kafka producer and consumer.](https://github.com/edenhill/kafkacat)
   * [Kafkacli - CLI and Go Clients to manage Kafka components (Kafka Connect & SchemaRegistry).](https://github.com/fhussonnois/kafkacli)
   * [Kafka Shell - ⚡A supercharged, interactive Kafka shell built on top of the existing Kafka CLI tools.](https://github.com/devshawn/kafka-shell)

## Schema 

   * [Javro is an interface allowing you to write Avro schemas with ease, to validate it, and to preview it into JSON format with samples.](https://javro.github.io/)
   * [Confluent Schema Registry - Confluent Schema Registry for Kafka.](https://github.com/confluentinc/schema-registry)
   * [Karapace - Karapace (Aiven) is the open source schema registry you can run on your own platforms. Alternative (compatible replacement) for Confluent Schema Registry, supports Avro and JSON Schema.](https://karapace.io/)

## Security 

   * [Kafka-Security-Manager - Manage your Kafka ACL at scale.](https://github.com/simplesteph/kafka-security-manager)
   * [Kafka-Encryption - About Kafka End to End Encryption.](https://github.com/QuickSign/kafka-encryption)

## Testing 

   * [Kafka Junit - This library wraps Kafka's embedded test cluster, allowing you to more easily create and run integration tests using JUnit against a "real" kafka server running within the context of your tests.No need to stand up an external kafka cluster!](https://github.com/salesforce/kafka-junit)
   * [Kafka-Streams-Test-Utils - Testing Kafka Streams.](https://kafka.apache.org/24/documentation/streams/developer-guide/testing.html)
   * [Mocked Streams - Scala DSL for Unit-Testing Processing Topologies in Kafka Streams.](https://github.com/jpzk/mockedstreams)
   * [Test Container for Apache Kafka - Testcontainers can be used to automatically instantiate and manage Apache Kafka containers.More precisely Testcontainers uses the official Docker images for Confluent OSS Platform.](https://www.testcontainers.org/modules/kafka/)
   
## Talks / Presentations

   * [Introduction to Apache Kafka by Joe Stein](https://www.youtube.com/watch?v=qc33qMUvR7c)
   * [Apache Kafka and the Next 700 Stream Processing Systems by Jay Kreps](https://www.youtube.com/watch?v=9RMOc0SwRro)
   * [Using Logs To Build a Solid Data Infrastructure - Martin Kleppmann (LinkedIn) ](http://www.ustream.tv/recorded/61479591)
   * [I ♥ Logs: Apache Kafka and Real-Time Data Integration](https://www.youtube.com/watch?v=aJuo_bLSW6s)
   * [Apache Kafka: Real-time Streaming and Data Pipelines with Apache Kafka by Joe Stein](https://www.youtube.com/watch?v=InAKDEk7H0M)
   * [Chris Curtin - AJUG - Apache Kafka](https://vimeo.com/63040812)
   * [Getting started guide on Apache Kafka by Learning Journal](https://www.youtube.com/playlist?list=PLkz1SCf5iB4enAR00Z46JwY9GGkaS2NON)
   * [Developing with the Go client for Apache Kafka](http://www.slideshare.net/charmalloc/developing-with-the-go-client-for-apache-kafka)
   * [Verisign - Apache Kafka 0.8 basic training](http://www.slideshare.net/miguno/apache-kafka-08-basic-training-verisign)
   * [Developing Real-Time Data Pipelines with Apache Kafka](http://www.slideshare.net/charmalloc/developingwithapachekafka-29910685)
   * [Infrastructure at Scale: Apache Kafka, Twitter Storm & Elastic Search (ARC303) | AWS re:Invent 2013](http://www.slideshare.net/AmazonWebServices/infrastructure-at-scale-apache-kafka-twitter-storm-elastic-search-arc303-aws-reinvent-2013)
   * [Real-time streaming and data pipelines with Apache Kafka](http://www.slideshare.net/charmalloc/real-timestreamingdata-pipelinesapachekafka)
   * [Building a Real-time Data Pipeline: Apache Kafka at LinkedIn](http://www.slideshare.net/Hadoop_Summit/building-a-realtime-data-pipeline-apache-kafka-at-linkedin)
   * [Kafka replication apachecon_2013](http://www.slideshare.net/junrao/kafka-replication-apachecon2013)
   * [Introduction and Overview of Apache Kafka](http://www.slideshare.net/mumrah/kafka-talk-tri-hug)

## Books

   * [Making sense of stream processing](http://www.confluent.io/making-sense-of-stream-processing-ebook)
   * [Designing Data-Intensive Applications](http://shop.oreilly.com/product/0636920032175.do)
   * [Effective Kafka - a hands-on guide to building robust and scalable event-driven applications](https://apachekafkabook.com/)
   * [Kafka: The Definitive Guide](https://www.confluent.io/wp-content/uploads/confluent-kafka-definitive-guide-complete.pdf)
   * [A fast-paced introduction to every aspect of working with Kafka you need to really reap its benefits.](https://www.manning.com/books/kafka-in-action)
   * [By the end of the book, you'll be ready to use Kafka Streams in your projects to reap the benefits of the insight your data holds quickly and easily.](https://www.manning.com/books/kafka-streams-in-action)
   * [Event Streaming with Kafka Streams and ksqlDB](https://www.manning.com/books/event-streaming-with-kafka-streams-and-ksqldb)
  
  
