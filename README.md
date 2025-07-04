🌐 Spring Boot Microservices Architecture – End-to-End Enterprise Implementation
This project is a complete, modular microservices-based architecture built using Spring Boot, showcasing best practices in scalability, resiliency, observability, and cloud-native deployment.

🚀 Overview
The system demonstrates real-world microservices concepts including API Gateway, Service Discovery, Centralized Configuration, Security, Observability, Event-Driven Communication, Containerization, and Kubernetes Deployment.

📁 Key Sections
🔧 Section 2 – Microservices Structure with H2 & Swagger
Structured services using clean modular architecture.

In-memory H2 database for local development.

Integrated Swagger/OpenAPI for API documentation and testing.

🐳 Section 4 – Containerization with Docker & Jib
Dockerized services using Google Jib and Buildpacks (no Dockerfile required).

Managed service orchestration with Docker Compose.

Proper startup dependencies and Docker networks to control service order and communication.

🛠️ Section 6 – Centralized Configuration with Spring Cloud Config
Implemented Spring Cloud Config Server and Config Client.

Enabled auto-refresh with Spring Cloud Bus.

Integrated GitHub Webhooks using Hookdeck to reflect config changes live in local development.

🛢️ Section 7 – Database Integration in Docker Compose
Added real databases (e.g. PostgreSQL, MySQL, MongoDB) in docker-compose.yml.

Defined proper service startup order, Docker volumes, and networks for seamless integration.

🔍 Section 8 – Service Discovery with Eureka
Registered all services with Eureka Server.

Used OpenFeign for declarative REST clients and dynamic service lookup via Eureka.

🌐 Section 9 – Spring Cloud Gateway (Reactive)
Implemented Spring Reactive API Gateway.

Added custom filters, path rewriting, and routing logic.

Configured centralized entry point to route traffic to microservices.

💪 Section 10 – Resilience with Resilience4j & Gateway Enhancements
Added Circuit Breaker, Retry, Rate Limiting (Redis), and Timeout using Resilience4j.

Implemented fallback mechanisms to handle service failures gracefully.

📊 Section 11 – Observability with Loki, Grafana, Prometheus, Tempo, AlloyDB
Centralized logging with Loki and Grafana.

Metrics collection with Prometheus.

Tracing with Tempo and log correlation.

Visualized logs, metrics, and traces in Grafana Dashboards.

🔐 Section 12 – Security with Keycloak and OAuth2
Integrated Keycloak as identity provider.

Secured APIs through the Spring Cloud Gateway using OAuth2 and JWT tokens.

Implemented role-based access control across services.

📡 Sections 13 & 14 – Event-Driven Architecture
Built event-driven communication using Spring Cloud Stream.

Used both Kafka and RabbitMQ as messaging brokers.

Integrated Spring Cloud Function for functional-style event handling.

☸️ Section 15 – Kubernetes Configs
YAML configurations for deploying all microservices and infrastructure to Kubernetes.

🧭 Section 16 – Helm Charts
Packaged and managed Kubernetes services using Helm for repeatable, versioned deployments.

🧬 Section 17 – Service Discovery in Kubernetes
Used Kubernetes-native discovery mechanisms and service objects for service registration and communication.

⚙️ Section 20 – Microservices Optimization with Shared Libraries
Extracted common logic into shared libraries (e.g., logging, security, exception handling).

Promoted DRY principles and reduced code duplication.

🏁 Tech Stack
Spring Boot, Spring Cloud, Spring Security

Keycloak, OAuth2, JWT

Docker, Jib, Buildpacks, Docker Compose

Kafka, RabbitMQ, Spring Cloud Stream

Kubernetes, Helm

Eureka, OpenFeign, API Gateway

Prometheus, Grafana, Loki, Tempo

MongoDB, PostgreSQL, H2, Redis

