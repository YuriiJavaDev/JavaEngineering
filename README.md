# 🏗️ Java Engineering

Welcome! This repository serves as a professional portfolio for mid-to-advanced backend projects. While my [Java Learning](https://github.com/YuriiJavaDev/JavaLearning) focuses on core syntax and basic algorithms, this section highlights complex systems, multi-layered architecture, and real-world engineering challenges.

## 🏛️ Featured Engineering Projects (With Full History)

*The following projects were developed under professional mentorship. They include full commit history to demonstrate the evolution of the code, architectural decisions, and the problem-solving process.*

---

### 💹 [StockMarketSystem_V0.1](https://github.com/YuriiJavaDev/stock-market-system)
A high-performance multithreaded simulation of a Stock Exchange.
* **Key Focus**: Advanced thread synchronization using `ExecutorService`, `ReentrantReadWriteLock`, and `CountDownLatch`.
* **Technical Highlights**: 
    * Implemented thread-safe `ConcurrentHashMap` for independent broker portfolios.
    * Developed real-time equity calculation and Profit/Loss (P/L) reporting logic.
    * Verified memory structure and object allocation using **VisualVM**.
    * The system is equipped with a "circuit breaker" mechanism that automatically suspends all trading operations if the market index falls below a critical threshold or if the trading session time has expired.

### 🎓 [UniversityCMS_V0.1](https://github.com/YuriiJavaDev/UniversityCMS)

University Schedule Content Management System (CMS) — a backend system for educational process management, implemented in Java using PostgreSQL and multi-layered architecture.

A comprehensive educational management system built with scalability in mind.
* **Key Focus**: Layered Architecture (DAO, Service, Controller) and robust data persistence.
* **Technical Highlights**: 
    * Designed complex PostgreSQL database schemas with multiple relationships.
    * Managed database versions using **Flyway** migrations.
    * Ensured code reliability with comprehensive **JUnit 5** and **Mockito** testing.

### 🏫 [SchoolManagementSystem_V0.1](https://github.com/YuriiJavaDev/SchoolManagementSystem_V0.1)

A console-based School Management System built with **Spring Boot**, focused on modern backend practices and automated database management.

* **Key Focus**: Transitioning from Core Java to the Spring ecosystem, implementing automated database evolution, and adopting containerized testing.
* **Technical Highlights**:
    * **Spring Data JPA & Hibernate**: Leveraged for efficient Object-Relational Mapping (ORM) and simplified data persistence layers.
    * **Flyway Migrations**: Implemented automated database schema versioning to ensure consistent environments across development and testing.
    * **Testcontainers**: Developed robust integration tests by spinning up real PostgreSQL instances in Docker containers during the build process.
    * **Architecture**: Followed a service-oriented approach to separate business logic from data access and CLI interaction.

---

## 🛠️ Practical Skills & Tools Demonstrated

* **Frameworks & Core Java**:
    * **Spring Boot**: Building production-ready applications with dependency injection and auto-configuration.
    * **Concurrency**: Managing thread lifecycles with `ExecutorService`, ensuring synchronization via `ReentrantReadWriteLock`, and using `CountDownLatch` for thread coordination.
* **Data Management & Persistence**:
    * **Spring Data JPA & Hibernate**: Implementing ORM patterns to map Java objects to relational tables efficiently.
    * **SQL & PostgreSQL**: Designing complex schemas, managing relationships, and ensuring ACID compliance.
    * **Database Migrations**: Using **Flyway** for version-controlled schema evolution.
* **Software Architecture**:
    * **Multi-tier (Layered) Architecture**: Separating concerns into Controller, Service, and DAO/Repository layers.
    * **Clean Code**: Refactoring based on professional mentorship to ensure maintainability and readability.
* **Testing & Quality Assurance**:
    * **Integration Testing**: Using **Testcontainers** to run tests against real Dockerized PostgreSQL instances.
    * **Unit Testing**: Verifying business logic with **JUnit 5** and mocking dependencies with **Mockito**.
* **Monitoring & Tooling**:
    * **Performance Profiling**: Monitoring heap memory, object allocation, and thread states using **VisualVM**.
    * **Build Tools**: Managing dependencies and project lifecycles with **Maven**.

---
