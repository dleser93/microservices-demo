# Event-Driven Microservices: Spring Boot, Kafka and Elasticsearch
This project was the practical part of the online course "Master event-driven microservices architecture with patterns using Spring boot, Spring cloud, Kafka and Elasticsearch" taught by Ali Gelenler, EA Algorithm on Udemy. The goal was to develop a microservice architecture from scratch using the most recent software platforms, technologies, libraries and tools, following best practices, applying microservices patterns and using Java, Spring boot, Spring cloud, Spring Security, Kafka and Elasticsearch. It also covers Event sourcing and Event-driven services using Kafka as the event store.

## Project Overview:

### Implemented Microservice Patterns Are:
- Externalized configuration with Spring Cloud Config
- CQRS with Kafka and Elastic search
- Api versioning for versioning of Rest APIs
- Service Registration and Discovery with Spring Cloud and Netflix Eureka
- Api Gateway with Spring Cloud Gateway
- Circuit breaker with Spring Cloud Gateway and Resilience4j
- Rate limiting with Spring Cloud Gateway and Redis to use Redis as the Rate limiter
- Distributed tracing with SLF4J MDC, Spring Cloud Sleuth and Zipkin
- Log aggregation with ELK stack (Elasticsearch, Logstash and Kibana)
- Client side load balancing with Spring Cloud Load Balancer
- Database per Service
- Messaging between microservices using Kafka

### Project Schema:
![alt text](https://github.com/dleser93/microservices-demo/blob/main/images/project_overview.png?raw=true)

### Prerequisites:
- Knowledge of Java
- Basic knowledge of Spring Framework
- Basic knowledge of Maven
- Back-end development experience
- Docker experience
- Twitter Developer Account (If you are using twitter data for stream)

## Running the Application:
- Clone the repo using ```git clone https://github.com/dleser93/microservices-demo.git```.
- Enter the correct credentials in twitter4j.properties file in twitter-to-kafka-service 
and enter your github password and url on application.yml file of config-server.
- Then run ```mvn install -DskipTests``` command.
- Then go to \docker-compose folder and run ```docker-compose up``` command to start the application.
