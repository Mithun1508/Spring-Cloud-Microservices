# Spring Cloud Sleuth Zipkin Microservice Log Tracing Server

![Spring cloud sleuth](https://github.com/Mithun1508/Spring-Cloud-Sleuth-Zipkin-Server-Microservice-Log-Tracing-u/assets/93249038/78d040b1-e4df-49f7-914f-ea323fc6468d)


## Overview

Spring Cloud Sleuth Zipkin Microservice Log Tracing Server is a distributed tracing system built with Spring Boot and Zipkin. It facilitates the gathering of timing data necessary for troubleshooting latency issues in service architectures. The system includes both the collection and lookup of this data, providing insights into the flow of requests through your microservices.

## Features

1. Distributed Tracing
End-to-End Monitoring: Trace requests from the entry point to different microservices, providing a holistic view of request flow.

Unique Trace IDs: Assign unique trace IDs to requests, making it easier to follow their journey through the system.

Span Information: Gather detailed information about each span in the request lifecycle.

2. Performance Analysis
   
Latency Detection: Identify and troubleshoot latency problems in the system.

Performance Bottleneck Identification: Pinpoint areas of the system causing performance bottlenecks.

3. Dependency Visualization
4. 
Microservices Interaction: Visualize dependencies between various microservices.

Service Interaction Flow: Understand how different services interact with each other.
## Prerequisites
Before you begin, ensure you have the following installed:

Java Development Kit (JDK)

Maven (for building the project)

## Getting Started

Follow these steps to set up and run the project locally:

1. Clone the repository:

   git clone https://github.com/Mithun1508/Spring-Cloud-Sleuth-Zipkin-Server-Microservice-Log-Tracing-u.git

   a) Navigate to the project directory:
   
   cd Spring-Cloud-Sleuth-Zipkin-Microservice-Log-Tracing-Server

   b) Build and run the application:
   
   ./mvnw spring-boot:run

   The application will be accessible at http://localhost:8080.


## Contributing
If you would like to contribute to the project, please follow the Contributing Guidelines.

## License
This project is licensed under the Apache-2.0 License - see the LICENSE file for details.


