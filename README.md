# Final-DevOps-Project-Por-olio-Grade-Assignment-DevSecOps-Microservices-Platform-Portfolio-Project-
A Python-based Microservices platform for managing users and tasks, with a strong emphasis on DevSecOps — security from the code stage to Production.
# DevSecOps Microservices Platform

## Overview
Production-grade DevSecOps platform with secure CI/CD pipeline.

## Architecture
- Microservices (Python)
- Kubernetes (multi-namespace)
- GitOps via ArgoCD

## CI/CD Flow
1. Commit
2. Jenkins pipeline
3. SAST (Bandit)
4. Dependency Scan
5. Image Scan (Trivy)
6. Push
7. ArgoCD deploy

## Security
- Non-root containers
- Network policies
- Image immutability
- Secrets management

## Run Locally
docker-compose up --build
