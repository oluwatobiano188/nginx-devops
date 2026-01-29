## Nginx Docker CI/CD Project

### Overview
Dockerized Nginx web server with automated CI pipeline using GitHub Actions.

### Features
- Lightweight Alpine-based Nginx image
- Custom Nginx configuration
- Automated Docker build on push

### Run Locally
```bash
docker build -t nginx-devops .
docker run -p 8080:80 nginx-devops
