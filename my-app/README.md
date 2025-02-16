# My App

This is a full-stack application with a PostgreSQL database, a Node.js backend, and a React frontend, deployed using Docker and Kubernetes.

## Features
- UI: React frontend
- Backend: Node.js with Express and PostgreSQL
- Deployment: Docker, Kubernetes, and Jenkins CI/CD

## Setup
To build and run locally:
```sh
docker-compose up -d
```

To deploy on Kubernetes:
```sh
kubectl apply -f k8s/
```
