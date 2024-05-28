# CDC-Kafka-Debezium-PostgreSQL
synchronizing two psql databases using kafka and debezium 

## Content 
In the context of handling reference data in an application with a microservices architecture, this repository implements change-data-capture (CDC) between databases. This approach provides a looser coupling at the application level by duplicating reference data across databases and then synchronizing them with the source for any changes.

## Debezium 
Debezium is an open source distributed platform for change data capture [debezium](https://debezium.io/)

## Kafka 
Apache Kafka is an open-source distributed event streaming platform used by thousands of companies for high-performance data pipelines, streaming analytics, data integration, and mission-critical applications. [kafka](https://kafka.apache.org/)


