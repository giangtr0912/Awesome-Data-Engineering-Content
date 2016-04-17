Sharing interesting and noteworthy Data Engineering content - namely blogs, podcasts, repos, books, videos, and MOOCs.  This was mostly curated by and for Fellows in the [Insight Data Engineering Fellows Program](http://insightdataengineering.com), and inspired by the [repo](https://github.com/igorbarinov/awesome-data-engineering) of one of our Fellows, Igor Barinov.

If you have ideas or other interesting resources, feel free to open an Issue or Pull Request.

# Table of Contents

# Technologies
All technologies are listed alphabetically in their given section.

## Overviews
* [Data Engineering Ecosystem](http://insightdataengineering.com/blog/pipeline_map.html)

## File Formats

### Avro

### ORCFiles

### Parquet

### Protocol Buffers

### Thrift

## File Systems

### Hadoop Distributed File System (HDFS)

### S3

#### Blogs
* [Excellent summary](https://medium.com/@markobonaci/the-history-of-hadoop-68984a11704) of the history of Hadoop by Marco Bonaci.  This post is also [read as a podcast](http://softwareengineeringdaily.com/2016/02/06/history-of-hadoop/) by Software Engineering Daily.

## Databases

### Overviews
* [Jepsen](https://aphyr.com/tags/Jepsen) - Kyle Kingsbury's (Aphyr) guide on distributed systems and databases, and how they fail. 

### Relational Databases

#### MySQL

#### Postgres

### Key-Value Databases

#### Redis

#### Riak

### Column-Family Databases

#### Accumulo

#### Cassandra

#### HBase

### Graph Databases

#### Neo4j

#### OrientDB

### Search Tools

#### Elasticsearch

#### Lucene

#### Solr

## General Batch Processing

### Hadoop MapReduce

#### Blogs
* [Excellent summary](https://medium.com/@markobonaci/the-history-of-hadoop-68984a11704) of the history of Hadoop by Marco Bonaci.  This post is also [read as a podcast](http://softwareengineeringdaily.com/2016/02/06/history-of-hadoop/) by Software Engineering Daily.

### Hadoop Abstractions

#### Cascalog

#### Cascading

#### Hadoop Streaming / mrjob

#### Hive

#### Pig

#### Scalding

### Spark

## Graph Processing

### Giraph

### GraphLab Create

### Spark GraphX

## Machine Learning Tools

### FlinkML

### H2O

### Mahout

### Spark MLlib

## Stream Processing

### Flink

#### Slides
* [Strata Talk](http://www.slideshare.net/KostasTzoumas/apache-flink-at-strata-san-jose-2016) by Kostas Tzoumas on Flink Streaming's capabilities.
* [Streaming Benchmark talk](http://www.slideshare.net/JamieGrier/extending-the-yahoo-streaming-benchmark) by Jamie Grier on extending Yahoo's Benchmark, based off this [blog](http://data-artisans.com/extending-the-yahoo-streaming-benchmark/)

#### Blogs
* [Asynchronous Snapshots Blog](http://data-artisans.com/high-throughput-low-latency-and-exactly-once-stream-processing-with-apache-flink/) by Data Artisans, and a summary in [the morning paper](https://blog.acolyer.org/2015/08/19/asynchronous-distributed-snapshots-for-distributed-dataflows/)  

#### Papers
* [Millwheel Paper](http://research.google.com/pubs/pub41378.html) which discusses Low Watermarks for Exactly-Once Semantics
* [Asynchronous Snapshots Barrier Paper](http://arxiv.org/abs/1506.08603) describing Flink's snapshot algorithm
* [Chandy-Lamport Paper](http://research.microsoft.com/en-us/um/people/lamport/pubs/chandy.pdf) on Distributed Snapshots, and a summary in [the morning paper](https://blog.acolyer.org/2015/04/22/distributed-snapshots-determining-global-states-of-distributed-systems/)  

### NiFi

### Samza

### Spark Streaming

### Storm


## Ingestion Tools

### Flume

### Logstash


## Messaging Queues / PubSub
### Kafka
#### Blogs
* [Part 1](http://www.confluent.io/blog/stream-data-platform-1/) and [Part 2]((http://www.confluent.io/blog/stream-data-platform-2/)) of Jay Krep's on streams in Kafka

#### Podcasts

#### Videos
 * [Video] (https://www.youtube.com/watch?v=aJuo_bLSW6s&feature=youtu.be) by Jay Kreps on logs, stream processing and Kafka

### RabbitMQ

### ZeroMQ

## Workflow and Scheduling

### Airflow

#### Podcasts
* [Interview with Maxime Beauchemin](Software Engineering Daily) on Airflow, Airpal, and Caravel on Software Engineering Daily. 

### Azkaban

### Luigi

### Oozie

## Cluster Management and Coordination

### Docker

### Kubernetes

### Mesos

### YARN

### Zookeeper

# Important Algorithms and Theorems

* [List of 100 Seminal Data Engineering Papers](https://www.linkedin.com/pulse/100-open-source-big-data-architecture-papers-anil-madan) from Anil Madan

## Distributed Systems

* [General Notes](https://github.com/aphyr/distsys-class) from Kyle Kingsbury (Aphyr) on Distributed Sytems

### Paxos

*  [Visualization of Paxos](http://harry.me/blog/2014/12/27/neat-algorithms-paxos/) with explanation

### RAFT

### MapReduce

### Distributed graph and machine learning algorithms

#### Papers
 * [Paper] (https://www.cs.utah.edu/~lifeifei/papers/mrknnj.pdf) on using z-values for implementing approximate k-nearest neighbors in a MapReduce framework.  There is also a [Background paper](http://cs.sjtu.edu.cn/~yaobin/papers/icde10_knn.pdf) on the topic, describing the non-distributed version.
 * [Paper] (http://ds.qcri.org/images/profile/tarek_elgamal/sigmod2015.pdf) on sPCA -- Scalable Principal Component Analysis

### Gossip Protocol

### Chandy-Lamport
* [Chandy-Lamport Paper](http://research.microsoft.com/en-us/um/people/lamport/pubs/chandy.pdf) on Distributed Snapshots, and a summary in [the morning paper](https://blog.acolyer.org/2015/04/22/distributed-snapshots-determining-global-states-of-distributed-systems/) 

### Load Balancing

### Transactions

### CAP Theorem
* [Blog](http://blog.thislongrun.com/2015/03/the-cap-theorem-series.html) on nuances of the CAP theorem by Nicolas Liochon

# Background and Interview Prep

* [Repo](https://github.com/prakhar1989/awesome-courses) of awesome computer science courses.

## General Guidance for Interviews
[Excellent post](http://blog.triplebyte.com/how-to-pass-a-programming-interview) on preparing for interview from TripleByte, both technically and strategically

## Data Structures and Algorithms

### MOOCs
* [Part 1](https://www.coursera.org/course/algo) and [Part 2](https://www.coursera.org/course/algo2) of Tim Roughgarden's MOOC, based off his Stanford course.

### Books
* [Cracking the Coding Interview](http://www.amazon.com/Cracking-Coding-Interview-6th-Programming/dp/0984782850/ref=sr_1_1?s=books&ie=UTF8&qid=1460873864&sr=1-1&keywords=cracking+the+coding+interview), with solutions in many languages [here](https://github.com/careercup/ctci)

### Practice Websites
* [Leetcode Online Judge](https://leetcode.com/)
* [HackerRank](https://www.hackerrank.com/)

## SQL and Database Design

### MOOCs
* [Jennifer Widom's self-paced MOOC](https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/about) from first principles, based off her Stanford course.

### Practice Websites
* [Leetcode Online Judge](https://leetcode.com/)

## System Design
* [Repo](https://github.com/checkcheckzz/system-design-interview) of many sytem design studies, resources, and strategies.

## Software Engineering Best Practices

## Programming Languages

## Learning Linux Commands

## Operating Systems and Networking
