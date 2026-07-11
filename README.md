# Backend Portfolio

Hi, I'm Jihun Jeong 👋

Junior Backend Developer specializing in Java & Spring Boot.

Interested in transaction consistency, concurrency control, event-driven architecture, and scalable backend systems.

---

# 🛠 Tech Stack

## Backend
- Java
- Spring Boot
- Spring Security
- JPA / Hibernate

## Database & Infrastructure
- MySQL
- Redis
- AWS(EC2 / RDS)

## Messaging & Concurrency
- Kafka
- Redisson

## DevOps & Tools
- Docker
- GitHub Actions
- IntelliJ IDEA
- VS Code
- Postman

---

# 📌 Projects

## 🛒 OneStop (Team Project)

A hybrid e-commerce platform combining a Coupang-style marketplace with a seller onboarding system, built to handle data consistency under high traffic, asynchronous event processing, and AI-powered shopping experiences.

### Project Highlights
- Reliable event-driven order and payment processing
- Context-specific concurrency-control strategies
- Multi-server real-time notification delivery
- AI-powered shopping assistance and review summarization
- Integration and performance testing with Testcontainers and k6

### My Contributions
- Designed and implemented the Cart, Order, Payment, Coupon, and Notification domains
- Implemented a polling-based Transactional Outbox with Spring Scheduler for reliable Kafka event publishing
- Built Redis Pub/Sub-based real-time notifications to ensure SSE delivery across multi-server instances
- Implemented pessimistic locking for inventory deduction, duplicate payment prevention, order cancellation, and coupon state transitions
- Implemented Redisson lock, Lua script, and atomic DECR strategies for concurrent coupon issuance
- Conducted Testcontainers-based integration tests

### Tech Stack
- Java 17
- Spring Boot 3.x
- Spring Security
- Spring Data JPA / QueryDSL
- Redis / Redisson
- Kafka
- MySQL
- Docker
- AWS EC2
- JUnit 5
- Testcontainers
- k6
- Spring AI

🔗 Repository  
[GitHub Repository](https://github.com/one-stop-project/one-stop-backend)

---

## 🌾 Agri Commerce Platform (Team Project)

E-commerce backend platform focused on concurrency control, Redis caching, coupon systems, and time-sale processing.

### Project Highlights
- Concurrency-controlled coupon issuance using Redis distributed locks
- Coupon validation and usage-policy enforcement
- Time-sale product processing

### My Contributions
- Led the team and managed repository, issue, branch, and pull request workflows
- Implemented JWT-based authentication and authorization
- Provisioned AWS EC2 and RDS infrastructure
- Built the GitHub Actions-based CI/CD pipeline
- Coordinated API design and development schedules across the team

### Tech Stack
- Java 17
- Spring Boot 3.x
- Spring Security / JWT
- Redis
- MySQL
- Docker
- AWS EC2 / RDS
- GitHub Actions

🔗 Repository  
[GitHub Repository](https://github.com/Agricultural-E-commerce-Platform/Agricultural-E-commerce-Platform)

---

## ☕ Coffee Order System (Personal Project)

Multi-server coffee ordering system focused on distributed locking and Kafka-based event processing.

### Technical Focus
- Designed the system for a multi-server environment
- Prevented concurrent point-update conflicts using Redis distributed locks
- Built Kafka-based asynchronous order processing
- Implemented a ranking system using Redis ZSet
- Validated concurrency behavior and performance through k6 load tests

### Tech Stack
- Java 17
- Spring Boot 3.x
- Redis
- Kafka
- Docker
- k6

🔗 Repository  
[GitHub Repository](https://github.com/doksakim7/Personal-Coffee-Project)

---

# 📚 Currently Learning

- Spring AI (LLM integration, tool calling)
- Monitoring & Incident Response (Prometheus, Grafana)
- Advanced Performance Analysis and Load Test Result Interpretation
- Distributed Systems Design

---

# 🔗 Links

- GitHub: https://github.com/doksakim7
- Velog: https://velog.io/@jhsky3118/posts
