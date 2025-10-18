# First DevOps Project

This repository provides links to the backend and frontend of the project.

- **Backend:** [first-devops-project-be](https://github.com/Myaneeeee/first-devops-project-be)  
- **Frontend:** [first-devops-project-fe](https://github.com/Myaneeeee/first-devops-project-fe)  

---

## 📘 Project Overview
![App Development and Deployment Flow](https://res.cloudinary.com/dqvlnzw9f/image/upload/v1760771462/first-devops-project_0_xkegu4.png)
A full-stack authentication application with user registration, login, and role-based access (user/admin). The project demonstrates an automated CI/CD pipeline and Kubernetes deployment workflow on AWS.

---

## Frontend
- Built with **React**, **Vite**, **TypeScript**, and **Tailwind CSS**  
- State management using **Context API**  
- Authentication handled with **JWT access/refresh tokens**  

---

## Backend
- Developed with **Express.js** and **PostgreSQL**  
- Database hosted on **AWS RDS** within a custom **VPC**, subnets, and security groups  

---

## Deployment
- Containerized using **Docker**  
- Images pushed to **AWS ECR**  
- Deployed on **AWS EKS** using Kubernetes manifests with **LoadBalancer services**  

---

## CI/CD Pipeline
- Automated using **Jenkins** on an **AWS EC2 instance**  
- Pipeline handles builds, Docker image pushes, and Kubernetes deployments  
- Triggered automatically through **GitHub Webhooks**  

---

## Monitoring
- Cluster metrics collected by **Prometheus**  
- Visualized using **Grafana** for performance monitoring  

---
