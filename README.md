# Node.js Docker App

A simple Node.js application containerized using Docker and pushed to Docker Hub.

##  Run using Docker Hub

```bash
docker pull agupt107/nodejs-docker-app:latest
docker run -p 3000:3000 agupt107/nodejs-docker-app:latest
```

##  Build Locally

```bash
docker build -t nodejs-docker-app .
docker run -p 3000:3000 nodejs-docker-app
```

## 🐳 Docker Hub

https://hub.docker.com/repository/docker/agupt107/hello-world-app/general