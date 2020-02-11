# Spring-Boot-Microservices-Demo

Steps to build the application:

Build Microservices individually with maven (mvn clean install):

1. MicroserviceDiscoveryServer
2. ProfileMicroserviceProducer
3. ProfileMicroserviceConsumer

Steps to run the application:

1. Start Eureka Server  - (java -jar MicroserviceDiscoveryServer-1.0.0.jar) Access in browser: http://localhost:1111/
2. Producer Application - (java -jar ProfileMicroserviceProducer-1.0.0.jar)
3. Consumer Application - (java -jar ProfileMicroserviceConsumer-1.0.0.jar) Access in browser: http://localhost:8080/
