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

Tools Used

```bash
- Docker
- Docker Compose
- GitHub Actions
- AWS EC2
- DockerHub
- Linux
- Git
```

CI/CD Workflow

```bash
Developer pushed code -> Github actions detects it -> Checkout Code -> Login with DockerHub -> build Docker image -> Push image to Docker Hub -> SSH into EC2 using applyeboy action -> navigate to project folder -> Docker compose pull and then docker compose up 
```

Deployment

```
Application automatically deploys to EC2 after every push to main branch.
```

More to come
