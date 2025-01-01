This project is my learning project containerize a basic web application using a microservices architecture with Docker.

# Project Overview
This application consists of three main components:

- Frontend: React-based web interface
- Backend: Python
- Database: PostgreSQL

# Project Structure

firsttime-docker/
- ├── frontend/
- │   ├── public/
- │   ├── src/
- │   │   ├── App.js
- │   │   └── ...
- │   ├── package.json
- │   ├── package-lock.json
- │   └── Dockerfile
- ├── backend/
- │   ├── app.py
- │   ├── requirements.txt
- │   └── Dockerfile
- ├── README.md
- └── docker-compose.yml

# Prerequisites

- Docker
- JavaScript/Node.js & Phytone
- Git

# Key Learning Points
- Docker Basics
Dockerfile syntax
Building images
Running containers
- Docker Compose
Service orchestration
Container networking
Environment variables
Volume management
- Microservices Concepts
Service separation
Inter-service communication
Data persistence
Container dependencies

# Next Steps
After mastering this basic setup, consider exploring:

Adding Redis for caching
Implementing Nginx as a reverse proxy
Setting up Docker networks
Adding monitoring with Prometheus and Grafana
Implementing CI/CD pipelines

# Command

- Build and start all services
docker-compose up

- Build and start in detached mode
docker-compose up -d

- Stop all services
docker-compose down

- View logs
docker-compose logs

- Rebuild services
docker-compose up --build

- Access container shell
docker exec -it container_name sh
