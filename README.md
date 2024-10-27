# Event-Driven Microservices: Spring Boot, Kafka and Elasticsearch
This project was the practical part of the online course "Master event-driven microservices architecture with patterns using Spring boot, Spring cloud, Kafka and Elasticsearch" taught by Ali Gelenler, EA Algorithm on Udemy. The goal was to develop a microservice architecture from scratch using the most recent software platforms, technologies, libraries and tools, following best practices, applying microservices patterns and using Java, Spring boot, Spring cloud, Spring Security, Kafka and Elasticsearch. It also covers Event sourcing and Event-driven services using Kafka as the event store.

## Project Overview:

![alt text](https://github.com/dleser93/microservices-demo/blob/main/images/project_overview.png?raw=true)



## Running the Application:
- Please enter the correct credentials in twitter4j.properties file in twitter-to-kafka-service 
and enter your github password and url on application.yml file of config-server
- Then run mvn install -DskipTests command
- Then run docker-compose up command in docker-compose folder
