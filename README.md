# Service Discovery Server

In an MSA environment, there is a need to apply service discovery patterns to maintain many services. The Service Discovery Server is required to register multiple services and to perform searches for registered services.
This repository is the one that creates the Netflix OSS Eureka Server among the Discovery Server Client-Side approaches.

##  Spring Cloud Netflix
[Spring Cloud Netflix](https://cloud.spring.io/spring-cloud-netflix/reference/html/) is Netflix's OSS service that supports the configuration of an integrated environment for Spring Boot Applications.

### 1. Service Discovery

It refers to an operation of identifying a location of a server for a specific operation in a server in which the location of each service is registered. We can use Spring Cloud Netflix - Eureka Server for Service Discovery.

### 2. Service Registry

Each service refers to registering and registering its location (IP) information on a specific server. We can use Spring Cloud Netflix - Eureka Client for Service Registry.

