# Spring-Boot-Microservices-Demo

## Steps to build the application:

Build Microservices individually with maven (mvn clean install):

        - MicroserviceDiscoveryServer
        - ProfileMicroserviceProducer
        - ProfileMicroserviceConsumer

Steps to run the application:

1. Start Eureka Server  
    
        - (java -jar MicroserviceDiscoveryServer-1.0.0.war) http://localhost:8761/
2. Producer Application 

        - (java -jar ProfileMicroserviceProducer-1.0.0.war)
3. Consumer Application 

        - (java -jar ProfileMicroserviceConsumer-1.0.0.war) http://localhost:1111/userProfiles
