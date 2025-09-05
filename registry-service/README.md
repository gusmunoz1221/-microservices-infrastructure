# registry-service
Central registry for all hotel booking microservices (User, Hotel, Rating) using Eureka Server for service discovery and load balancing.
# Registry Service 🗂️

Service Registry (Eureka Server) for service discovery in the hotel booking microservices system.

---

## 📌 About
This service acts as a **central registry** where all microservices (User, Hotel, Rating, etc.) register themselves.  
It enables **service discovery** so that microservices can locate each other without hard-coded URLs.

---

## ✨ Features
- Centralized **service registry** using **Spring Cloud Netflix Eureka Server**.
- Provides **high availability** when configured in clusters.
- Enables **load balancing** and **fault tolerance** by allowing clients to fetch available service instances.

---

## 🛠️ Tech Stack
- **Java 21+**
- **Spring Boot 3+**
- **Spring Cloud Netflix Eureka Server**
- **Maven**

---

## ⚡ How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/gusmunoz1221/registry-service.git
