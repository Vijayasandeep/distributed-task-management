# TaskFlow Pro - Distributed Task Management Platform

## Architecture
- **Frontend:** React + Redux Toolkit
- **Backend:** Spring Boot Microservices
- **Database:** PostgreSQL + MongoDB + Redis
- **Message Queue:** RabbitMQ
- **Deployment:** Docker + AWS ECS

## Quick Start
```bash
# Start local environment
docker-compose up -d

# Start backend services
cd backend && ./start-services.sh

# Start frontend
cd frontend && npm start
