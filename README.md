# StreamGen - Realtime Data Streaming

## Introduction

This project involves constructing a comprehensive data engineering pipeline that spans the entire process, starting from data ingestion, progressing through processing, and concluding with storage. The project leverages a resilient technological stack, incorporating Apache Airflow, Python, Apache Kafka, Apache Zookeeper, Apache Spark, and Cassandra. To enhance deployment flexibility and scalability, all components are containerized using Docker.

## System Architecture

![System Architecture]()

The project is designed with the following components:

- **Data Source**: We use `randomuser.me` API to generate random user data for our pipeline.
- **Apache Airflow**: Responsible for orchestrating the pipeline and storing fetched data in a PostgreSQL database.
- **Apache Kafka and Zookeeper**: Used for streaming data from PostgreSQL to the processing engine.
- **Control Center and Schema Registry**: Helps in monitoring and schema management of our Kafka streams.
- **Apache Spark**: For data processing with its master and worker nodes.
- **Cassandra**: Where the processed data will be stored.

## Technologies

- Apache Airflow
- Python
- Apache Kafka
- Apache Zookeeper
- Apache Spark
- Cassandra
- PostgreSQL
- Docker
