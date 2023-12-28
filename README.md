## Big Data Architecture for Social Media-Based Event Tracking and Monitoring with Apache Kafka, Parquet, Spark Streaming, Spark NLP, Apache Airflow, and Tableau
In this architecture, we leverage a set of powerful technologies to build a scalable and efficient system for tracking and monitoring events based on social media data. Let's break down the workflow of the project:
## Architecture 

![Capture d'écran 2023-12-26 135739](https://github.com/Helk20/A-big-data-architecture-for-Social-network--based-event-tracking-and-monitoring/assets/92260626/56f6cdf3-abef-4247-851d-a7286f1d5c65)

## Project Workflow

The project workflow is designed to achieve efficient event tracking and monitoring from social media data. The following steps outline the process:

1. **Data Ingestion with Apache Kafka:** Social media data is ingested in real-time using Apache Kafka, ensuring a scalable and distributed event streaming platform.

2. **Data Processing with Spark Streaming:** Spark Streaming processes the ingested data in real-time, allowing for the extraction of meaningful insights.

3. **Natural Language Processing with Spark NLP:** Spark NLP is utilized for natural language processing tasks on the social media text data, extracting sentiments and entities.

4. **Workflow Orchestration with Apache Airflow:** Apache Airflow serves as the orchestrator, scheduling and managing workflows to ensure efficient data processing.

5. **Data Visualization with Tableau:** Processed data is visualized and analyzed using Tableau, providing an interactive interface for exploring insights.


## Applications
This project will start a docker cluster which gives access to the following frameworks/technologies.

| Framework/Technology         | Version            |
| ---------------------------- | ------------------ |
| Hadoop                       | 3.2.1              |
| Mini-Conda                   | 4.12.0             |
| Python                       | 3.9                |
| Spark                        | 3.2.2 (Scala 2.12) |
| Apache Airflow               | 2.3.3              |
| Apache Zeppelin              | 0.10.1             |
| Hive                         | 2.3.2              |
| Confluent Kafka              | 5.4.0-ce           |
| Confluent Schema Registry    | 5.4.0-ce           |
| Confluent Control Center     | 5.4.0              |

## Running the cluster
To start the cluster run the following command from the project directory.
```sh
docker-compose up
```

## Access docker containers
```sh
docker exec -it <container-name> or <container-id> /bin/bash
```

All steps are descriped in our guide file ...

## Contributors
- Houda EL KORAINI
- Rabab FAHSSI

Thank you for your interest in our project! We look forward to hearing from you and appreciate your support.
