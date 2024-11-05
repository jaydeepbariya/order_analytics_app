# Real-Time Order and Analytics Platform (ROAP)

A scalable, microservices-based platform for managing orders, processing payments, tracking inventory, and generating real-time analytics. Designed to showcase advanced backend development skills in Java, Kafka-based event streaming, containerized deployment, and more.

---

## 🚀 Features

- **User Management**: Secure user registration and authentication with JWT.
- **Order Processing**: Real-time order handling with status tracking.
- **Inventory Management**: Automated stock updates based on orders.
- **Payment Processing**: Mock payment integration for order finalization.
- **Analytics Dashboard**: Tracks key metrics from orders and payments.
- **Notification System**: Sends alerts based on order and payment events.
- **Scalability**: Microservices architecture allows independent scaling of services.

## 🛠️ Technology Stack

- **Backend**: Java, Spring Boot, Spring Security, Hibernate
- **Microservices**: Spring Cloud, REST APIs
- **Event Streaming**: Apache Kafka
- **Database**: PostgreSQL
- **Cache**: Redis
- **Containerization**: Docker
- **CI/CD**: Jenkins
- **Deployment**: AWS, Nginx, Unix

## 📁 Architecture Overview

ROAP uses a microservices architecture, allowing independent scaling and modular functionality. Services communicate via Kafka for real-time updates, Redis for caching, and PostgreSQL for persistent data.

### Microservices

1. **User Service**: Manages user profiles and authentication.
2. **Order Service**: Handles order creation, updates, and retrieval.
3. **Inventory Service**: Manages product stock and inventory.
4. **Payment Service**: Processes payments and updates order statuses.
5. **Analytics Service**: Consumes events for reporting and analysis.
6. **Notification Service**: Sends notifications for significant events.

---

## 🧰 Project Structure

