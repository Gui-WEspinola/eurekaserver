## Eureka Server Microserve integration project

### 1. Description

This is a project to train and implement a system of APIs working in a microservice oriented environment.
In the current repository, we are creating a server to control access to individual applications. The APIs were designed to
with a Customer and Credit Card relationship in mind, and the goal is to implement logic to check available cards 
for a given customer, and issue news cards if possible.

As a whole, the main goal of the project is to practice development using Java Spring Cloud framework, while integrating various
microservices and technologies.

### 2. Links for other Microservices

[Gateway for microservice integration](https://github.com/Gui-WEspinola/mscloudgateway)

[Microservice of Customers](https://github.com/Gui-WEspinola/msclientes)

[Microservice of Credit Card](https://github.com/Gui-WEspinola/mscartoes)

[Microservice for Credit Rating](https://github.com/Gui-WEspinola/ms-avaliador-credito)

### 3. Features

Some of the technologies used to develop and test the current applications are:

1. Spring Cloud with microservices integration, making use of Spring Cloud OpenFeign.
2. **RabbitMQ** implementing an asynchronous messaging system.
3. Security using **Oauth2** and **JWT** token, while using **Keycloak** to manage credentials.
4. **Docker** implemented on all applications.
5. **Postman/Insomnia** to test endpoints and requisitions.
6. Logs implemented.


