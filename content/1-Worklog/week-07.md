---
title: "Week 07: Containers & ECS"
weight: 7
---

## 1. Weekly Summary

| Item | Description |
|---|---|
| **Week** | Week 07 |
| **Topic** | Docker, Amazon ECR, and Amazon ECS (Fargate) |
| **Focus** | Containerization, task definitions, services, and serverless containers |

## 2. Daily Worklog Timeline

| Day | Date | Main Task | Activities | Result |
|---|---|---|---|---|
| **Monday** | Day 1 | Dockerization | Wrote Dockerfiles for a Node.js microservice | Container runs locally |
| **Tuesday** | Day 2 | Amazon ECR | Created ECR repositories and pushed Docker images | Images securely hosted on AWS |
| **Wednesday** | Day 3 | ECS Task Definitions | Created task definitions with IAM roles and resource limits | Task definition registered |
| **Thursday** | Day 4 | ECS Fargate Services | Deployed services on AWS Fargate behind an ALB | App running without managing servers |
| **Friday** | Day 5 | ECS Auto Scaling | Configured target tracking scaling for ECS services | Containers scale automatically |

## 3. Technical Skills Learned

| Technology | Knowledge Gained |
|---|---|
| **Docker** | Images, Containers, Dockerfiles |
| **Amazon ECR** | Container registries, image scanning |
| **Amazon ECS / Fargate** | Clusters, Services, Task Definitions, Serverless compute for containers |

## 4. Challenges & Solutions

| Challenge | Solution |
|---|---|
| **Container Health Checks** | ALB marked containers unhealthy due to slow startup. Adjusted grace period in ECS Service |

## 5. Weekly Reflection

| Category | Description |
|---|---|
| **Learning Outcome** | Gained proficiency in deploying containerized microservices on AWS |
| **Improvement Area** | Understanding ECS service discovery and App Mesh |
| **Next Step** | Automate infrastructure provisioning with CloudFormation/Terraform |
