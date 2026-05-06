Project Name: DevOps Starter Project

Description:
This project demonstrates a basic DevOps workflow:
- A simple Node.js application
- Containerized using Docker
- Version controlled with GitHub
- CI/CD pipeline using GitHub Actions
- Deployment (to be added)

Goal:
To showcase end-to-end DevOps practices for learning and job readiness.

Architecture:

```bash
GitHub Push
   ↓
GitHub Actions
   ↓
Build Docker Image
   ↓
Push to DockerHub
   ↓
SSH into EC2
   ↓
docker compose pull
docker compose up -d
```
