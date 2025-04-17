# eazy-store
eazy-store as a reference-quality full-stack project with Java Spring Boot + Microservices + ReactJS, and you want it to contain all relevant documents.

# 🛍️ eazy-store

> A full-stack e-commerce platform built with **Java Spring Boot microservices** and a **ReactJS frontend** — modular, event-driven, and container-ready.

---

## 📖 Overview

**eazy-store** is a fully-featured reference project that demonstrates how to build a production-grade, microservices-based e-commerce system using:
- Java 17
- Spring Boot & Spring Cloud
- ReactJS frontend
- RabbitMQ/Kafka for messaging
- Docker for deployment

🔎 It's perfect for learning or kickstarting your own microservice-based application.

---

## 📦 Core Features

- ✅ Product Catalog & Search  
- 🛒 Shopping Cart & Orders  
- 🧾 User Registration & Login (JWT)  
- 💳 Payment Simulation  
- 📦 Inventory Management  
- 📬 Asynchronous Messaging (RabbitMQ/Kafka)  
- 🔍 Service Discovery (Eureka)  
- 🛡️ Role-Based Authentication  

🗂️ **eazy-store** also includes a **complete documentation suite**, covering every part of the stack:

| Document                       | Description                                   |
|-------------------------------|-----------------------------------------------|
| `project-overview.md`         | Introduction to the system                    |
| `architecture.md`             | Microservices layout and flow diagrams        |
| `microservices.md`            | Description of each service's responsibility  |
| `api-specs.md`                | REST endpoints per service                    |
| `database-design.md`          | ER diagrams and DB schemas                    |
| `authentication.md`           | JWT flow and RBAC setup                       |
| `messaging.md`                | Async messaging with RabbitMQ/Kafka           |
| `frontend-react.md`           | React project structure and integration       |
| `docker-deployment.md`        | Running the entire stack with Docker Compose  |
| `dev-environment.md`          | Dev setup, env variables, ports, etc.         |

📁 All docs are located in the [`/docs`](./docs) folder.

---

## 🧱 Tech Stack

### 🔙 Backend
- Java 17+
- Spring Boot
- Spring Cloud (Eureka, Gateway, Config)
- Spring Security + JWT
- OpenFeign
- RabbitMQ / Kafka
- MySQL / PostgreSQL

### 🖥️ Frontend
- ReactJS (with Axios or Redux Toolkit)
- TailwindCSS / Material UI

### 🐳 DevOps & Tools
- Docker & Docker Compose
- Postman (API testing)
- Swagger UI for documentation
- Flyway or Liquibase (DB migrations)

---

## 🛠️ Installation Guide

### 📍 Prerequisites

- Java 17+
- Node.js & npm
- Maven
- Docker & Docker Compose

### 🔄 Clone & Setup

```bash
git clone https://github.com/your-username/eazy-store.git
cd eazy-store

