# Docker Compose App with Nginx Reverse Proxy on EC2

## Overview
This project demonstrates deploying a multi-container application using Docker Compose and exposing it through an Nginx reverse proxy on AWS EC2.

## Technologies Used
- Docker & Docker Compose (v2)
- Nginx
- AWS EC2 (Ubuntu)
- Linux
- GitHub

## Architecture
- Web service container (Nginx)
- Redis container (internal)
- Nginx reverse proxy on EC2

## How It Works
- Docker Compose manages multi-container setup
- Nginx acts as a reverse proxy routing traffic to the web container
- Application is deployed on AWS EC2

## How to Run
```bash
docker compose up -d

