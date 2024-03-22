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
