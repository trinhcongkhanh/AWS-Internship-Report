---
title: "Week 10: Security & Compliance"
weight: 10
---

## 1. Weekly Summary

| Item | Description |
|---|---|
| **Week** | Week 10 |
| **Topic** | AWS KMS, AWS WAF, Amazon GuardDuty, and AWS Config |
| **Focus** | Data encryption, threat detection, web firewalls, and compliance auditing |

## 2. Daily Worklog Timeline

| Day | Date | Main Task | Activities | Result |
|---|---|---|---|---|
| **Monday** | Day 1 | AWS KMS | Created CMKs and enforced encryption on S3 buckets and EBS | Data at rest encrypted |
| **Tuesday** | Day 2 | AWS Certificate Manager | Provisioned SSL/TLS certificates for Application Load Balancers | Data in transit encrypted (HTTPS) |
| **Wednesday** | Day 3 | AWS WAF | Attached Web Application Firewall to ALB to block SQLi and XSS | Application protected from common web exploits |
| **Thursday** | Day 4 | Amazon GuardDuty | Enabled GuardDuty for intelligent threat detection | Monitoring for malicious IP activity |
| **Friday** | Day 5 | AWS Config | Set up Config rules to ensure no S3 buckets are public | Continuous compliance tracking active |

## 3. Technical Skills Learned

| Technology | Knowledge Gained |
|---|---|
| **AWS KMS** | Symmetric/Asymmetric keys, Envelope Encryption |
| **AWS WAF** | Web ACLs, Managed rule groups |
| **AWS Config & GuardDuty** | Continuous auditing and intelligent threat detection |

## 4. Challenges & Solutions

| Challenge | Solution |
|---|---|
| **WAF Blocking Legitimate Traffic** | False positives from WAF blocked an API endpoint. Adjusted the rule priority and added a safe-list condition |

## 5. Weekly Reflection

| Category | Description |
|---|---|
| **Learning Outcome** | Learned to implement security at every layer of the AWS architecture |
| **Improvement Area** | Automating remediation of AWS Config rule violations via Systems Manager |
| **Next Step** | Implement comprehensive monitoring and logging solutions |
