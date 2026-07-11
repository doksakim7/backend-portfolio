# Backend Portfolio

Hi, I'm Jihun Jeong 👋

Junior Backend Developer specializing in Java & Spring Boot.

Interested in backend architecture, concurrency control, distributed systems, and scalable backend services.

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
- Transactional Outbox pattern for reliable event publishing
- Kafka-based asynchronous messaging (order, payment, delivery events)
- Redis distributed lock, pessimistic lock, and optimistic lock strategies applied by business context
- Real-time notifications via Redis Pub/Sub + SSE
- AI shopping assistant and AI review summarization (Spring AI)
- Load testing with k6 and integration testing with Testcontainers

### My Role
- Owned Cart, Order, Payment, Coupon, and Notification domains
- Implemented payment retry logic (`@Retryable` in `PaymentRetryFacade`)
- Verified system reliability through k6 load testing and Testcontainers-based integration tests

### Tech Stack
- Java 17
- Spring Boot 3
- Spring Security
- Spring Data JPA / QueryDSL
- Redis (Redisson) / Kafka
- MySQL
- Docker
- AWS EC2

🔗 Repository  
[GitHub Repository](https://github.com/one-stop-project/one-stop-backend)

---

## 🌾 Agri Commerce Platform (Team Project)

E-commerce backend platform focused on concurrency control, Redis caching, coupon systems, and time-sale processing.

### Project Highlights
- Redis distributed lock
- Coupon validation
- Time-sale processing

### My Role
- JWT authentication implementation
- AWS infrastructure setup
- CI/CD pipeline setup using GitHub Actions
- Team leadership and repository management

### Tech Stack
- Java
- Spring Boot
- Redis
- MySQL
- Docker
- AWS

🔗 Repository  
[GitHub Repository](https://github.com/Agricultural-E-commerce-Platform/Agricultural-E-commerce-Platform)

---

## 💳 Payment System (Team Project)

Backend payment service handling payment approval, refund processing, webhook synchronization, and point transactions.

### Project Highlights
- Webhook idempotency
- Transaction consistency
- Point refund processing
- Payment / Order separation
- JWT authentication

### My Role
- Membership policy management API
- Membership history query API
- Domain responsibility separation improvement
- API response standardization

### Tech Stack
- Java
- Spring Boot
- JPA
- MySQL

🔗 Repository  
[GitHub Repository](https://github.com/Payment-system-4team/payment-system-project)

---

## ☕ Coffee Order System (Personal Project)

Multi-server coffee ordering system focused on distributed locking and Kafka-based event processing.

### Key Features
- Redis distributed lock
- Kafka asynchronous event processing
- Redis ZSet ranking system
- Concurrency control
- k6 load testing

### My Role
- Backend system design
- Redis distributed lock implementation
- Kafka event processing
- Redis ZSet ranking implementation
- Concurrency handling
- Load testing with k6

### Tech Stack
- Java
- Spring Boot
- Redis
- Kafka
- Docker

🔗 Repository  
[GitHub Repository](https://github.com/doksakim7/Personal-Coffee-Project)

---

# 📚 Currently Learning

- Distributed Systems
- Kafka Event-Driven Architecture
- Concurrency Control
- Cloud Infrastructure
- Scalable Backend Design

---

# 🔗 Links

- Velog  
  https://velog.io/@jhsky3118/posts
