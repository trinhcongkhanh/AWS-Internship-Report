---
title: "Tuần 07: Containers & ECS"
weight: 7
---

## 1. Tóm tắt tuần

| Hạng mục | Mô tả |
|---|---|
| **Tuần** | Tuần 07 |
| **Chủ đề** | Docker, Amazon ECR, và Amazon ECS (Fargate) |
| **Mục tiêu chính** | Containerization, task definitions, services, và serverless containers |

## 2. Nhật ký công việc hàng ngày

| Ngày | Kế hoạch | Tác vụ chính | Hoạt động chi tiết | Kết quả |
|---|---|---|---|---|
| **Thứ Hai** | Ngày 1 | Dockerization | Viết Dockerfile cho một ứng dụng Node.js microservice | Container chạy thành công trên máy local |
| **Thứ Ba** | Ngày 2 | Amazon ECR | Tạo kho lưu trữ ECR và push Docker images lên AWS | Images được lưu trữ bảo mật trên AWS |
| **Thứ Tư** | Ngày 3 | ECS Task Definitions | Tạo task definition, cấp quyền IAM và giới hạn tài nguyên CPU/RAM | Task definition được đăng ký |
| **Thứ Năm** | Ngày 4 | ECS Fargate Services | Deploy dịch vụ lên AWS Fargate thông qua ALB | App hoạt động mà không cần quản lý máy chủ |
| **Thứ Sáu** | Ngày 5 | ECS Auto Scaling | Cấu hình Target Tracking Scaling cho dịch vụ ECS | Containers tự động scale theo tải |

## 3. Kỹ năng công nghệ học được

| Công nghệ | Kiến thức đạt được |
|---|---|
| **Docker** | Images, Containers, Dockerfiles |
| **Amazon ECR** | Private registry cho Container, quét bảo mật images |
| **Amazon ECS / Fargate** | Clusters, Services, Task Definitions, chạy container không cần server |

## 4. Thử thách & Giải pháp

| Thử thách | Giải pháp |
|---|---|
| **Lỗi Health Check của Container** | ALB báo lỗi vì app khởi động chậm. Sửa bằng cách tăng 'Health check grace period' trong ECS |

## 5. Phản ngẫm hàng tuần (Reflection)

| Hạng mục | Mô tả |
|---|---|
| **Kết quả học tập** | Sử dụng thành thạo quy trình đưa ứng dụng container lên AWS |
| **Điểm cần cải thiện** | Tìm hiểu thêm về ECS Service Discovery và AWS App Mesh |
| **Bước tiếp theo** | Tự động hóa triển khai hạ tầng bằng CloudFormation/Terraform |
