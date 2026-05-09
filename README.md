# Microservices Containerization Project

## 📌 Overview
This project demonstrates containerization of a microservices-based Node.js application using Docker and Docker Compose.

It includes 4 services:
- User Service (Port 3000)
- Product Service (Port 3001)
- Order Service (Port 3002)
- Gateway Service (Port 3003)

---

## ⚙️ Tech Stack
- Node.js
- Express.js
- Docker
- Docker Compose

---

## 📁 Project Structure
Microservices/
├── user-service/
├── product-service/
├── order-service/
├── gateway-service/
├── docker-compose.yml
└── README.md


---

## 🚀 How to Run the Project

### 1. Build and start containers

```bash
docker compose up --build

Check running containers
docker ps

Service Endpoints
Service	URL
User Service	http://localhost:3000

Product Service	http://localhost:3001

Order Service	http://localhost:3002

Gateway Service	http://localhost:3003

Stop Services
docker compose down




Screenshots:
Running containers (docker ps)

Browser outputs
Docker compose running logs

Author
Mithun
Microservices Containerization Assignment

