---
title: "Week 05: Databases (RDS & DynamoDB)"
weight: 5
---

## 1. Weekly Summary

| Item | Description |
|---|---|
| **Week** | Week 05 |
| **Topic** | Relational and NoSQL Databases on AWS |
| **Focus** | Amazon RDS, Multi-AZ deployments, Read Replicas, Amazon DynamoDB |

## 2. Daily Worklog Timeline

| Day | Date | Main Task | Activities | Result |
|---|---|---|---|---|
| **Monday** | Day 1 | RDS Provisioning | Launched a MySQL RDS instance in private subnets | Database running securely |
| **Tuesday** | Day 2 | Multi-AZ & Backups | Enabled Multi-AZ for high availability and automated backups | Fault-tolerant DB architecture |
| **Wednesday** | Day 3 | Read Replicas | Created a Read Replica to offload analytical queries | Read performance improved |
| **Thursday** | Day 4 | DynamoDB Basics | Created NoSQL tables and defined Partition/Sort keys | DynamoDB tables active |
| **Friday** | Day 5 | Application Integration | Connected Python app to both RDS and DynamoDB | App successfully querying databases |

## 3. Technical Skills Learned

| Technology | Knowledge Gained |
|---|---|
| **Amazon RDS** | Managed relational databases, Multi-AZ, Backups, Parameter Groups |
| **Amazon DynamoDB** | NoSQL, Partition Keys, Capacity Modes (On-Demand vs Provisioned) |

## 4. Challenges & Solutions

| Challenge | Solution |
|---|---|
| **DynamoDB Hot Partitions** | Redesigned partition keys using a composite ID to distribute read/write capacity evenly |

## 5. Weekly Reflection

| Category | Description |
|---|---|
| **Learning Outcome** | Mastered managed database setups and understood NoSQL data modeling |
| **Improvement Area** | Deepening knowledge of DynamoDB Global Secondary Indexes (GSIs) |
| **Next Step** | Migrating monolithic apps to Serverless architectures |
