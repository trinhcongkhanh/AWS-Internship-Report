---
title: "Week 09: CI/CD Pipelines"
weight: 9
---

## 1. Weekly Summary

| Item | Description |
|---|---|
| **Week** | Week 09 |
| **Topic** | AWS CodeCommit, CodeBuild, CodeDeploy, and CodePipeline |
| **Focus** | Continuous Integration, Continuous Deployment, and build automation |

## 2. Daily Worklog Timeline

| Day | Date | Main Task | Activities | Result |
|---|---|---|---|---|
| **Monday** | Day 1 | Source Control | Migrated code to AWS CodeCommit repositories | Repositories secured with IAM |
| **Tuesday** | Day 2 | AWS CodeBuild | Created buildspec.yml to compile code and run unit tests | Automated tests passing in CodeBuild |
| **Wednesday** | Day 3 | Docker in CodeBuild | Updated buildspec to build and push Docker images to ECR | Images pushed automatically on commit |
| **Thursday** | Day 4 | AWS CodeDeploy | Configured Blue/Green deployment for ECS Fargate | Zero-downtime deployment mechanism ready |
| **Friday** | Day 5 | AWS CodePipeline | Orchestrated Source -> Build -> Deploy into a single pipeline | Fully automated CI/CD working |

## 3. Technical Skills Learned

| Technology | Knowledge Gained |
|---|---|
| **AWS CodePipeline** | Pipeline orchestration, stages, artifacts |
| **AWS CodeBuild** | Buildspec files, build environments |
| **AWS CodeDeploy** | Deployment groups, Blue/Green routing |

## 4. Challenges & Solutions

| Challenge | Solution |
|---|---|
| **IAM Permissions for CodeBuild** | Build failed due to missing ECR push permissions. Added specific inline policy to the CodeBuild service role |

## 5. Weekly Reflection

| Category | Description |
|---|---|
| **Learning Outcome** | Mastered end-to-end deployment automation on AWS |
| **Improvement Area** | Integrating third-party tools like SonarQube into CodePipeline |
| **Next Step** | Implement security guardrails and compliance checks |
