# 🚀 API Gateway Microservice

[![Java Version](https://img.shields.io/badge/Java-21-green.svg)](https://www.oracle.com/java/)
[![Spring Boot Version](https://img.shields.io/badge/Spring_Boot-3.4.6-brightgreen.svg)](https://spring.io/projects/spring-boot)
[![Maven](https://img.shields.io/badge/Maven-3.8.7-blue.svg)](https://maven.apache.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A reactive API Gateway built with **Spring Boot 3.4.6** and **Java 21**. It uses **Spring Cloud Gateway** for routing, **Consul** for service discovery, and **Resilience4J** for fault tolerance and circuit breaking.  

---

## ✨ Features

- Fully reactive, non-blocking API Gateway with **Spring WebFlux**  
- Dynamic service discovery with **Consul**  
- Circuit breaker pattern with **Resilience4J** for resilience  
- Monitoring and management with **Spring Boot Actuator**  
- Easy route configuration via Spring Cloud Gateway  

---

## 🚧 Future Improvements

- Secure routes with OAuth2 / JWT  
- Distributed tracing (Spring Cloud Sleuth / Zipkin)  
- Enhanced logging & monitoring  
- Centralized config with Spring Cloud Config Server  

---

## 🛠 Tech Stack

| Technology                  | Version     |
| -------------------------- | ----------- |
| Java                       | 21          |
| Spring Boot                | 3.4.6       |
| Spring Cloud Gateway       | Latest      |
| Spring WebFlux             | Included    |
| Spring Cloud Consul        | Latest      |
| Spring Cloud Circuit Breaker (Resilience4J) | Latest |
| Maven                      | 3.8.7+      |

---

## 📋 Prerequisites

- Java 21 JDK ([Download](https://www.oracle.com/java/technologies/javase/jdk21-archive-downloads.html))  
- Maven 3.8.7+ ([Download](https://maven.apache.org/download.cgi))  
- Consul agent installed and running ([Download](https://www.consul.io/downloads))  

---

## 🚀 Getting Started

### Running Consul locally (dev mode)

```bash
consul agent -dev

```

## ⚙️ Build & Run

```bash
# Clone repo
git clone https://github.com/yourusername/api-gateway.git
cd api-gateway

# Build
mvn clean install

# Run
mvn spring-boot:run

```

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💼 Author

Developed by Supunsan
