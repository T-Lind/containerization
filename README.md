# Containerization
Author: T-Lind

This project demonstrates container creation, replication, and orchestration using Docker and Docker Compose on AWS EC2.

Tech stack:
- AWS EC2 (Ubuntu)
- Docker
- Docker Compose
- NGINX

Implementation:
- One base NGINX container image
- Five identical replicas
- Five unique services using the same image

Instructions:
1. Build image: `docker build -t project2-nginx .`
2. Start services: `docker compose up -d`
3. Access services via EC2 IP and ports 8081–8085
