---
title: "Week 08: Infrastructure as Code (IaC)"
weight: 8
---

## 1. Weekly Summary

| Item | Description |
|---|---|
| **Week** | Week 08 |
| **Topic** | AWS CloudFormation and AWS Cloud Development Kit (CDK) |
| **Focus** | Infrastructure automation, templates, stacks, and programmatic provisioning |

## 2. Daily Worklog Timeline

| Day | Date | Main Task | Activities | Result |
|---|---|---|---|---|
| **Monday** | Day 1 | CloudFormation Basics | Wrote YAML templates for VPC and Subnets | Network stack deployed successfully |
| **Tuesday** | Day 2 | Parameters & Outputs | Refactored templates to be reusable across environments | Dynamic parameters working |
| **Wednesday** | Day 3 | AWS CDK Setup | Initialized CDK projects in TypeScript | CDK bootstrapped in AWS account |
| **Thursday** | Day 4 | CDK Constructs | Built an ECS Fargate service using higher-level CDK constructs | Complex infra deployed in 50 lines of code |
| **Friday** | Day 5 | Stack Updates | Practiced stack drifts, updates, and rollbacks | Understood IaC state management |

## 3. Technical Skills Learned

| Technology | Knowledge Gained |
|---|---|
| **AWS CloudFormation** | Stacks, Templates, Parameters, Resources, Outputs |
| **AWS CDK** | TypeScript, Constructs, Synth, Deploy |

## 4. Challenges & Solutions

| Challenge | Solution |
|---|---|
| **Circular Dependencies** | Resolved a circular dependency error in CloudFormation between Security Groups |

## 5. Weekly Reflection

| Category | Description |
|---|---|
| **Learning Outcome** | Realized the immense power of defining infrastructure as code |
| **Improvement Area** | Writing custom CloudFormation macros and CDK custom resources |
| **Next Step** | Implement CI/CD pipelines to deploy IaC automatically |
