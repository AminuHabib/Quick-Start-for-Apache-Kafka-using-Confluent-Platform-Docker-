# Quick-Start-for-Apache-Kafka-using-Confluent-Platform-Docker-

Use this quick start to get up and running with Confluent Platform and its main components using Docker containers. This quick start uses Confluent Control Center included in Confluent Platform for topic management and event stream processing using ksqlDB.

In this quick start, you create Apache Kafka® topics, use Kafka Connect to generate mock data to those topics, and create ksqlDB streaming queries on those topics. You then go to Control Center to monitor and analyze the event streaming queries.
## Prerequisites:
Docker
- Docker version 1.11 or later is installed and running.
- Docker Compose is installed. Docker Compose is installed by default with Docker for Mac.
- Docker memory is allocated minimally at 6 GB. When using Docker Desktop for Mac, the default Docker memory allocation is 2 GB. You can change the default allocation to 6 GB in Docker. Navigate to Preferences > Resources > Advanced.
- Internet connectivity
- Operating System currently supported by Confluent Platform
- Networking and Kafka on Docker
- Configure your hosts and ports to allow both internal and external components to the Docker network to communicate
