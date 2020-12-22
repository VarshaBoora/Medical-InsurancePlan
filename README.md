# Medical-InsurancePlan

# Springboot-Based Bigdata Prototype

Architecture diagram

Contents
In this project, we will develop a REST Api to parse a JSON schema model divided into three demos


1. Develop a Spring Boot based REST Api to parse a given sample JSON schema.
2. Save the JSON schema in a redis key value store.
3. Demonstrate the use of operations like GET, POST and DELETE for the first prototype demo.
4. Regress on your model and perform additional operations like PUT and PATCH.
5. Secure the REST Api with a security protocol RS256 with JWT.
6. Adding Elasticsearch capabilities, implementing parent-child relation for data searching and operation.
7. Using RedisMQ for REST API queueing


Tools required to develop project 

Java
Maven
Redis Server
Elasticsearch and Kibana(Local or cloud based)
Build and Run
Run as Spring Boot Application in any IDE.

Querying Elasticsearch

Run both the application Basic Service and Consumer Message Queue(CMQ). CMQ application will create the indexes.
Run POST query from Postman to parse usecase.txt
Run custom search queries as per your use case, in parent-child rules.
