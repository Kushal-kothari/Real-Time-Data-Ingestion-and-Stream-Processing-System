# Realtime Data Streaming Project

## Table of Contents
- [Introduction](#introduction)
- [System Architecture](#system-architecture)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)

## Introduction

This project demonstrates a robust, end-to-end real-time data pipeline solution, from data ingestion through processing to final storage. The system is containerized using **Docker** for easy scalability and deployment, leveraging industry-standard tools like **Apache Airflow**, **Kafka**, **Spark**, and **Cassandra**. The architecture supports real-time user data streaming with fault-tolerant processing and storage mechanisms, ensuring high availability and scalability.

## System Architecture

![System Architecture](https://github.com/Kushal-kothari/Real-Time-Data-Ingestion-and-Stream-Processing-System/blob/main/Data%20engineering%20architecture.png)

The data pipeline consists of the following key components:

- **Data Source**: Fetches random user data through API.
- **Apache Airflow**: Manages task orchestration and workflow automation.
- **Apache Kafka & Zookeeper**: Provides real-time data streaming and synchronization across services.
- **Apache Spark**: Handles data processing, including transformation and aggregation.
- **Cassandra**: Serves as the storage for processed data.
- **Docker**: Ensures easy deployment and management of all services in a containerized environment.

## Key Features

- **End-to-End Pipeline**: From ingestion, processing, to storage, this system demonstrates an efficient data flow.
- **Real-time Data Streaming**: Stream over **50,000 API requests per minute**, making it highly scalable.
- **Distributed Architecture**: Leverages **Kafka** and **Spark** for processing and **Cassandra** for fault-tolerant data storage.
- **Automation**: Managed by **Airflow**, ensuring an automated workflow with real-time updates.

## Technologies Used

- **Apache Airflow** for orchestration
- **Apache Kafka** and **Zookeeper** for real-time data streaming and synchronization
- **Apache Spark** for distributed data processing
- **Cassandra** for high-availability data storage
- **PostgreSQL** for task management
- **Docker** for containerization

## Getting Started

1. Clone the repository:
    ```bash
    git clone <your-repo-link>
    ```

2. Navigate to the project directory:
    ```bash
    cd realtime-data-streaming
    ```

3. Start the services using Docker Compose:
    ```bash
    docker-compose up
    ```

For further details on the setup and execution, please check out the linked documentation within the project.
