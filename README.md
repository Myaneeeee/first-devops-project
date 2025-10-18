# First DevOps Project
This repository contains links to the First DevOps Project's backend and frontend repositories.

Backend Repository: https://github.com/Myaneeeee/first-devops-project-be
Frontend Repository: https://github.com/Myaneeeee/first-devops-project-fe

## Description:
Built a full-stack authentication app with user registration, login, and role-based access (user/admin). The frontend uses React with Vite, Tailwind, and TypeScript, managing state with context and using JWT access/refresh tokens. The backend is built with Express.js and PostgreSQL.

The PostgreSQL database is hosted on AWS RDS inside a custom VPC with subnets and security groups. Both frontend and backend are containerized with Docker, pushed to AWS ECR, and deployed on an EKS Kubernetes cluster using manifests for deployments and LoadBalancer services.

Set up CI/CD with Jenkins on an EC2 instance to automate builds, tests, ECR pushes, and Kubernetes deployments via a Groovy pipeline triggered by GitHub webhooks. Added monitoring with Prometheus and Grafana.
