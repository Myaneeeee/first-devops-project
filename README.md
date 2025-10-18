# First DevOps Project

This repository links to the backend and frontend of the First DevOps Project.

- **Backend:** https://github.com/Myaneeeee/first-devops-project-be  
- **Frontend:** https://github.com/Myaneeeee/first-devops-project-fe  

## Project Overview

A full-stack authentication application with user registration, login, and role-based access (user/admin).  

### Frontend
- Built with **React**, **Vite**, **TypeScript**, and **Tailwind CSS**  
- State management using **Context API**  
- Authentication handled with **JWT access/refresh tokens**  

### Backend
- Built with **Express.js** and **PostgreSQL**  
- Database hosted on **AWS RDS** within a custom **VPC**, subnets, and security groups  

### Deployment
- Containerized with **Docker**  
- Images pushed to **AWS ECR**  
- Deployed on **AWS EKS** using Kubernetes manifests with **LoadBalancer services**  

### CI/CD
- Automated with **Jenkins** running on an **EC2 instance**  
- Pipeline handles builds, tests, Docker pushes, and Kubernetes deployments  
- Triggered via **GitHub webhooks**  

### Monitoring
- Integrated **Prometheus** and **Grafana** for cluster monitoring
