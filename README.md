# Java-Microservices-Complete-Course
Java-Microservices-Complete-Course


# Java Microservices Guide

## Part 1: Understanding and Building Java Microservices

### 1. Introduction to Microservices
- What is Microservice?
- Need for Microservices
- Principles of Microservices
- Characteristics of a Microservice
- Benefits of Microservices
- Limitations of Microservices
- Comparison with other Architecture Styles

### 2. Spring Boot and Spring Cloud in Microservices
- What is Spring Cloud?
- Spring Cloud Configuration - Centralized, Versioned Configuration
- Dynamic configuration updates with Spring Cloud Bus
- Service discovery with Spring Cloud Netflix Eureka
- Client-side load balancing with Spring Cloud Netflix Ribbon  5b
- Circuit breakers with Spring Cloud Netflix Hystrix
- Declarative REST clients with Feign
- Zuul proxy as the API gateway

### 3. Resilience and Isolation Patterns
- The circuit breaker pattern
- Leverage Hystrix
- Hystrix console
- Troubleshooting

### 4. Distributed Tracing using Spring Cloud Sleuth and Zipkin
- What Problem Distributed Tracing Solves?
- How Distributed Tracing Works
- Distributed Tracing using Spring Cloud Sleuth
- Distributed Tracing with Zipkin

### 5. Advanced Circuit Breaker Implementation
- Replacement capabilities available in new Spring Cloud version
- Adding Resilience4j
- Actuator /health Endpoint
- RestTemplate client & Circuit Breaker Fallback method
- Feign Client & Circuit Breaker Fallback method
- Circuit Breaker configuration properties
- Configure Access to Actuator endpoints
- Monitoring Circuit Breaker events in Actuator

### 6. Retry Patterns with Resilience4j
- @Retry annotation
- Aspect Order
- Configuration properties

### 7. Routing and Load Balancing
- Spring Cloud Gateway for routing
- Load balancing strategies and custom filters
- What is a service gateway?
- Spring Cloud Gateway Architecture
- Configuring routes in Spring Cloud Gateway
- Dynamically reload route configuration
- Built-in Predicates and Filters Factories
- Creating Custom Filters
- Global Filters using Spring Cloud Gateway
- Netflix Eureka Discovery Service Implementation

### 8. Monitoring with Prometheus and Micrometer
- Metrics collection and monitoring setup
- Custom metrics and Prometheus integration

### 9. Event-Driven Architecture
- Messaging with RabbitMQ and Spring Cloud Stream
- Publishing and consuming messages

### 10. Stream Processing Using Spring Cloud Data Flow
- What is a Data Pipeline?
- Architectural Overview
- Components of Spring Cloud Data Flow
- Steps for Installing Spring Cloud Data Flow

### 11. Scaling Microservices with Spring Cloud
- Approaching for Autoscaling
- Scaling with resource constraints
- Scaling during specific time periods
- Scaling based on the message queue length
- Scaling based on Business Parameters

## Part 2: Advanced Topics and Deployment

### 1. Deep Dive into Microservices Patterns
- Comparison with monolithic applications
- Event-driven systems and transaction management
- Saga patterns for distributed transactions

### 2. Axon Server for Event Sourcing
- Setup and configuration
- Running with Docker

### 3. CQRS and Event Sourcing
- Implementing CQRS with Spring Boot
- Event sourcing fundamentals with Axon Framework

### 4. Data Management in Microservices
- Database patterns and CAP theorem
- Handling data consistency and transactions

### 5. Cross-Cutting Concerns
- Addressing concerns with patterns like Sidecar

### 6. Containerization and Orchestration
- Docker fundamentals and microservices
- Container orchestration with Kubernetes

### 7. Deployment on AWS
- AWS ECS and Fargate for microservices deployment
- CI/CD with AWS CodePipeline

