---
title: "Week 04: Storage Solutions"
weight: 4
---

## 1. Weekly Summary

| Item | Description |
|---|---|
| **Week** | Week 04 |
| **Topic** | AWS Storage Services: S3, EBS, and EFS |
| **Focus** | Object storage, block storage, shared file systems, and lifecycle policies |

## 2. Daily Worklog Timeline

| Day | Date | Main Task | Activities | Result |
|---|---|---|---|---|
| **Monday** | Day 1 | S3 Basics | Created buckets, enabled versioning and server-side encryption | Secure bucket provisioned |
| **Tuesday** | Day 2 | S3 Lifecycle Rules | Configured rules to transition old objects to Glacier | Cost-optimized storage policy active |
| **Wednesday** | Day 3 | EBS Volumes | Created, attached, and expanded EBS volumes on running EC2s | Zero-downtime volume expansion |
| **Thursday** | Day 4 | EBS Snapshots | Automated daily EBS snapshots using Data Lifecycle Manager | Backup strategy implemented |
| **Friday** | Day 5 | Amazon EFS | Mounted EFS across multiple EC2 instances in different AZs | Shared file system functional |

## 3. Technical Skills Learned

| Technology | Knowledge Gained |
|---|---|
| **Amazon S3** | Buckets, Objects, Versioning, Storage Classes, Lifecycle |
| **Amazon EBS** | Volume types (gp3, io2), Snapshots, DLM |
| **Amazon EFS** | NFS mounting, cross-AZ sharing |

## 4. Challenges & Solutions

| Challenge | Solution |
|---|---|
| **EFS Mount Timeout** | Resolved by allowing NFS port (2049) in the EFS Security Group from EC2 SG |

## 5. Weekly Reflection

| Category | Description |
|---|---|
| **Learning Outcome** | Understood the distinct use cases for Block, File, and Object storage |
| **Improvement Area** | Exploring S3 replication for disaster recovery |
| **Next Step** | Implement managed databases to decouple state from compute |
