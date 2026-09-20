---
title: "Week 11: Monitoring, Logging & Observability"
weight: 11
---

## 1. Weekly Summary

| Item | Description |
|---|---|
| **Week** | Week 11 |
| **Topic** | Amazon CloudWatch, AWS CloudTrail, and AWS X-Ray |
| **Focus** | Metrics, Alarms, Logs analysis, and distributed tracing |

## 2. Daily Worklog Timeline

| Day | Date | Main Task | Activities | Result |
|---|---|---|---|---|
| **Monday** | Day 1 | CloudWatch Metrics & Alarms | Created custom dashboards and CPU/Memory alarms | Proactive alerts configured via SNS |
| **Tuesday** | Day 2 | CloudWatch Logs | Installed unified CloudWatch Agent on EC2 to collect application logs | Centralized logging achieved |
| **Wednesday** | Day 3 | AWS CloudTrail | Enabled multi-region trails and analyzed API activity | Full audit log of account activities available |
| **Thursday** | Day 4 | CloudWatch Log Insights | Wrote queries to parse JSON logs and identify error spikes | Log troubleshooting accelerated |
| **Friday** | Day 5 | AWS X-Ray | Instrumented Node.js application to trace requests through API Gateway, Lambda, and DynamoDB | Distributed tracing visualized |

## 3. Technical Skills Learned

| Technology | Knowledge Gained |
|---|---|
| **Amazon CloudWatch** | Dashboards, Alarms, Logs, Log Insights |
| **AWS CloudTrail** | API auditing, Event history |
| **AWS X-Ray** | Service maps, Trace analysis |

## 4. Challenges & Solutions

| Challenge | Solution |
|---|---|
| **High Log Storage Costs** | Configured log retention policies to 30 days and exported older logs to S3 Glacier |

## 5. Weekly Reflection

| Category | Description |
|---|---|
| **Learning Outcome** | Mastered observability tools to quickly troubleshoot and monitor cloud health |
| **Improvement Area** | Creating more complex CloudWatch Metric Filters for custom business metrics |
| **Next Step** | Final project integration and Architecture review |
