# Microservices Containerization Project

## Overview
This project demonstrates containerization of a microservices-based Node.js application using Docker and Docker Compose.

It includes 4 services:
- User Service (Port 3000)
- Product Service (Port 3001)
- Order Service (Port 3002)
- Gateway Service (Port 3003)

---

## Tech Stack
- Node.js
- Express.js
- Docker
- Docker Compose

---

## Project Structure
Microservices/
├── user-service/
├── product-service/
├── order-service/
├── gateway-service/
├── docker-compose.yml
└── README.md


---

## How to Run the Project

### 1. Build and start containers

bash
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
<img width="1251" height="81" alt="image" src="https://github.com/user-attachments/assets/f59e92c7-4da9-4bff-93a8-50ba11e5525b" />

Browser outputs
<img width="1246" height="695" alt="image" src="https://github.com/user-attachments/assets/fb9347ec-cd98-4060-87ca-8cb23140d8ca" />
<img width="1245" height="689" alt="image" src="https://github.com/user-attachments/assets/0e393647-4237-4ea4-b186-2c8f0776a7ff" />
<img width="1246" height="691" alt="image" src="https://github.com/user-attachments/assets/13ded852-079d-4e0f-a28a-d84354bf32b9" />
<img width="1250" height="697" alt="image" src="https://github.com/user-attachments/assets/1fe17be3-1c04-45ea-8f64-5520254bda72" />


Docker compose running logs
<img width="1254" height="143" alt="image" src="https://github.com/user-attachments/assets/fdacba65-f52d-4dae-b8da-4571fa8e6a17" />

Author
Mithun
Microservices Containerization Assignment

