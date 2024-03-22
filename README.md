# Realtime Data Streaming | End-to-End Data Engineering Project


## Table of Contents

- [Introduction](#introduction)
- [System Architecture](#system-architecture)
- [What You'll Learn](#what-youll-learn)
- [Technologies](#technologies)
- [Getting Started](#getting-started)

## Introduction

This project serves as a comprehensive guide to building an end-to-end data engineering pipeline. It covers each stage from data ingestion to processing and finally to storage,
utilizing a robust tech stack that includes Apache Airflow, Python, Apache Kafka, Apache Zookeeper, Apache Spark, and Cassandra. Everything is containerized using Docker for
ease of deployment and scalability.

## System Architecture

![System Architecture](https://github.com/ZeroTwoDataRW/DE-Stream-Project-Random-Generated-User-Data/assets/163179337/5f3028e3-823f-47fd-bed8-1bafa6d3dd29)

The project is designed with the following components:

- Data Source: We use randomuser.me API to generate random user data for our pipeline.
- Apache Airflow: Responsible for orchestrating the pipeline and storing fetched data in a PostgreSQL database.
- Apache Kafka and Zookeeper: Used for streaming data from PostgreSQL to the processing engine.
- Control Center and Schema Registry: Helps in monitoring and schema management of our Kafka streams.
- Apache Spark: For data processing with its master and worker nodes.
- Cassandra: Where the processed data will be stored.

## What You'll Learn

- Setting up a data pipeline with Apache Airflow
- Real-time data streaming with Apache Kafka
- Distributed synchronization with Apache Zookeeper
- Data processing techniques with Apache Spark
- Data storage solutions with Cassandra and PostgreSQL
- Containerizing your entire data engineering setup with Docker

## Technologies

- Apache Airflow
- Python
- Apache Kafka
- Apache Zookeeper
- Apache Spark
- Cassandra
- PostgreSQL
- Docker

## Getting Started

1. Clone the repository:
```bash
 https://github.com/ZeroTwoDataRW/DE-Stream-Project-Random-Generated-User-Data.git
```
2. Navigate to the project directory:
```bash
cd DE-Stream-Project-Random-Generated-User-Data
```

4. Run Docker Compose to spin up services:
```bash
docker-compose up -d
```


![installing_venv_python3](https://github.com/ZeroTwoDataRW/DE-Stream-Project-Random-Generated-User-Data/assets/163179337/8808fe10-abd8-4d10-a649-6cb73f271e14)

![checking_formated_data_results](https://github.com/ZeroTwoDataRW/DE-Stream-Project-Random-Generated-User-Data/assets/163179337/69ad894e-db71-4c27-8229-16b3f5f90264)

![kafka-and-zookeeper-connected](https://github.com/ZeroTwoDataRW/DE-Stream-Project-Random-Generated-User-Data/assets/163179337/6b9c775b-ebd1-4dc0-bef5-02df08c1bd7e)

![installed_kafka_python_library](https://github.com/ZeroTwoDataRW/DE-Stream-Project-Random-Generated-User-Data/assets/163179337/059630d6-02a4-46b4-82c3-b83c116ed498)

![docker-images-installed](https://github.com/ZeroTwoDataRW/DE-Stream-Project-Random-Generated-User-Data/assets/163179337/df98b13f-2d68-4391-8908-73ef07dbabfb)

![sending_data_to_kafka_broker](https://github.com/ZeroTwoDataRW/DE-Stream-Project-Random-Generated-User-Data/assets/163179337/a0a61f3f-691a-48cf-9a86-d66d39785217)

![kafka_topic_created](https://github.com/ZeroTwoDataRW/DE-Stream-Project-Random-Generated-User-Data/assets/163179337/7d377fd7-22c6-427c-ae76-fd9246161751)

![running_images](https://github.com/ZeroTwoDataRW/DE-Stream-Project-Random-Generated-User-Data/assets/163179337/b54aec25-ecbf-4061-bb3e-f4000509dcb2)

![checking_airflow_working](https://github.com/ZeroTwoDataRW/DE-Stream-Project-Random-Generated-User-Data/assets/163179337/ee156571-efe6-423a-b166-14b5a9c10db6)

![user_automation_dag](https://github.com/ZeroTwoDataRW/DE-Stream-Project-Random-Generated-User-Data/assets/163179337/ef5491d5-606a-43a0-a60c-ad9dcf3594af)

![all_docker_images_running](https://github.com/ZeroTwoDataRW/DE-Stream-Project-Random-Generated-User-Data/assets/163179337/b60a5187-9ccf-46a9-9cc8-5fba8df7e3e2)

![dag_is_running](https://github.com/ZeroTwoDataRW/DE-Stream-Project-Random-Generated-User-Data/assets/163179337/c169571a-654e-40f4-b565-2020834bcac8)

![adding_git_to_project](https://github.com/ZeroTwoDataRW/DE-Stream-Project-Random-Generated-User-Data/assets/163179337/fb6d309e-0641-46ce-bd9a-d3054785b4f1)

![keyspace_and_table_created_successfully](https://github.com/ZeroTwoDataRW/DE-Stream-Project-Random-Generated-User-Data/assets/163179337/462361ec-2912-4b5c-82cb-05631f57e8a7)

![describe_spark_streams](https://github.com/ZeroTwoDataRW/DE-Stream-Project-Random-Generated-User-Data/assets/163179337/0f5077df-b8a4-4206-9e11-a9bb6641cc04)







