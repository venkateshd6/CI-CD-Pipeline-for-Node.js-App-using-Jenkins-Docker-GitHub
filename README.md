# CI-CD-Pipeline-for-Node.js-App-using-Jenkins-Docker-GitHub
## Overview
Built an automated CI/CD pipeline to deploy a Node.js app on AWS EC2 using Jenkins and Docker.

## Tech Stack
- Jenkins
- GitHub
- Docker & Docker Compose
- AWS EC2 (Ubuntu)

## Pipeline Stages
- Code checkout (GitHub)
- Build & Test (Jenkins)
- Docker Image Build
- Push to EC2
- Auto-deploy with Docker Compose

## Key Features
- Automated build, test, and deploy steps
- Health checks and rollback strategy
- Notifications on failure

## How to Run
1. Set up Jenkins on EC2
2. Configure webhook for GitHub push
3. Define Jenkinsfile with all stages
4. Deploy Docker containers with docker-compose up -d

## Outcome
- Enabled faster releases
- Reduced human error in deployment
