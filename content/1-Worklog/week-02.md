---
title: "Week 02: VPC & Networking"
weight: 2
---

## 1. Weekly Summary

| Item | Description |
|---|---|
| **Week** | Week 02 |
| **Topic** | Virtual Private Cloud (VPC) design and Network Routing |
| **Focus** | Public/Private subnets, NAT Gateways, Route Tables, Security Groups |

## 2. Daily Worklog Timeline

| Day | Date | Main Task | Activities | Result |
|---|---|---|---|---|
| **Monday** | Day 1 | VPC Architecture | Designed a 3-tier VPC architecture | Architecture diagram approved |
| **Tuesday** | Day 2 | Subnets & Routing | Created public and private subnets, attached IGW | Basic routing works |
| **Wednesday** | Day 3 | NAT Gateway | Provisioned NAT Gateway for private subnet internet access | Private instances can update OS |
| **Thursday** | Day 4 | Security Groups & NACLs | Configured stateful and stateless firewalls | Network isolated and secured |
| **Friday** | Day 5 | VPC Peering | Tested VPC peering between two environments | Cross-VPC communication established |

## 3. Technical Skills Learned

| Technology | Knowledge Gained |
|---|---|
| **Amazon VPC** | Subnetting, CIDR blocks, Route Tables |
| **Network Security** | Security Groups vs Network ACLs |

## 4. Challenges & Solutions

| Challenge | Solution |
|---|---|
| **Asymmetric Routing** | Fixed route tables to ensure return traffic routes correctly through the peered VPC |

## 5. Weekly Reflection

| Category | Description |
|---|---|
| **Learning Outcome** | Deepened understanding of cloud networking and CIDR math |
| **Improvement Area** | Understanding advanced routing patterns like Transit Gateway |
| **Next Step** | Deploying compute resources inside the new VPC |
