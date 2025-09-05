# -microservices-infrastructure
Microservices infrastructure repository: contains Eureka Server, API Gateway, and Config Server for microservices architecture. Provides service discovery, centralized configuration, and request routing.

# Microservices Infrastructure

This repository contains the foundational infrastructure for a Spring Boot microservices architecture:

- **Eureka Server**: service registry for discovering microservices.
- **API Gateway**: routes requests to microservices and provides load balancing and filters.
- **Config Server**: centralized configuration management for all microservices.

Usage:
1. Start Eureka Server.
2. Start Config Server (connects to this repo or Git configuration repo).
3. Start API Gateway.
4. Start your microservices (user-service, hotel-service, rating-service).

