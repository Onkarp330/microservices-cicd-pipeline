# Microservices CI/CD Pipeline

This project demonstrates an automated CI/CD pipeline using GitHub Actions.

## Stack

- Python Flask
- Docker
- GitHub Actions

## Pipeline Workflow

1. Developer pushes code
2. GitHub Actions builds Docker image
3. Container runs automatically

## Run Locally

Build container

```
docker build -t devops-sample .
```

Run container

```
docker run -p 5000:5000 devops-sample
```
