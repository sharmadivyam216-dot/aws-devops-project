 # AWS DevOps Project

## Live Deployment

Application URL:

http://13.232.145.159:4200

---

## Project Overview

A full-stack web application deployed on AWS EC2 using Docker and Docker Compose.

The project demonstrates:

- Cloud deployment on AWS
- Containerization using Docker
- Multi-container orchestration using Docker Compose
- Backend API development with Spring Boot
- Frontend application deployment
- MySQL database integration

---

## Tech Stack

### Frontend
- React/Angular
- Nginx
- Docker

### Backend
- Java
- Spring Boot
- Maven
- Docker

### Database
- MySQL 8.0

### DevOps & Cloud
- AWS EC2
- Ubuntu Linux
- Docker Compose
- Git
- GitHub

---

## Architecture

```text
                Internet
                    |
                    v
        +----------------------+
        |      AWS EC2         |
        |   Ubuntu 24.04 LTS   |
        +----------+-----------+
                   |
            Docker Compose
                   |
     +-------------+-------------+
     |             |             |
     v             v             v
 Frontend      Backend        MySQL
  Nginx      Spring Boot      8.0
 Port 4200   Port 8080      Port 3306
```

## Deployment

Infrastructure:

- AWS EC2 (t3.small)
- Ubuntu 24.04
- Docker
- Docker Compose
- GitHub

---

## Challenges Faced

- Docker container startup failures
- MySQL compatibility issues
- AWS Security Group configuration
- SSH connectivity troubleshooting
- Container networking issues

---

## Solutions Implemented

- Migrated MySQL image to version 8.0
- Updated Docker configuration
- Configured AWS Security Groups
- Verified services using Docker logs
- Deployed application successfully on AWS EC2

---

## Screenshots

Add screenshots here.
