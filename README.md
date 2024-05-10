## Microservice Project with Eureka, API Gateway, Rate Limiting, and Okta Authentication
This project demonstrates a microservice architecture using Spring Boot, Eureka for service registration, Zuul as an API Gateway, rate limiting with JMeter, and Okta for API authentication. Configuration for the services is fetched from a GitHub repository.

## Components:
UserService: Microservice for managing user-related operations.
RatingService: Microservice for managing hotel ratings.
HotelService: Microservice for managing hotel-related operations.

## APIGateway: Microservice acting as a gateway for all APIs. Handles authentication, rate limiting, and routes requests to appropriate services.
Service Registry (Eureka): Service registry where microservices are registered.
GitHub Repository: Holds configuration files for microservices.

## Technologies Used:
Spring Boot: For building microservices.
Eureka Client: To register microservices with the service registry.
API Gateway Microservice : For routing and filtering of requests.
JMeter: For testing rate limiting.
Okta: For API authentication.
GitHub: For storing configuration files.

## Setup Instructions:
Clone the GitHub repository to your local machine.
git clone <repository-url>

## Configure Okta:
Create an Okta account.
Set up an Okta application for API authentication.
Configure Okta settings in the APIGateway microservice.

## Configure GitHub:
Store configuration files (e.g., application.properties) for microservices in the GitHub repository.

## Build and Run Microservices:
Build each microservice using Maven.
Run Eureka server.
Run microservices and register them with Eureka.
Run APIGateway microservice.

## Test Rate Limiting:
Use JMeter to simulate API requests and test rate limiting functionality.

## Usage:
Once the microservices are up and running, APIs can be accessed through the APIGateway microservice.
Requests will be authenticated using Okta.
Rate limiting will be enforced as per configuration.

## Attachements
Here I attached my swagger documentaion of apis.
Here I attached my all postman api collection for your reference.
