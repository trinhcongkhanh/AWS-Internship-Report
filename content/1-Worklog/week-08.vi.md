---
title: "Tuần 08: Hạ tầng dưới dạng mã (IaC)"
weight: 8
---

## 1. Tóm tắt tuần

| Hạng mục | Mô tả |
|---|---|
| **Tuần** | Tuần 08 |
| **Chủ đề** | AWS CloudFormation và AWS Cloud Development Kit (CDK) |
| **Mục tiêu chính** | Tự động hóa hạ tầng, templates, stacks, và lập trình hạ tầng |

## 2. Nhật ký công việc hàng ngày

| Ngày | Kế hoạch | Tác vụ chính | Hoạt động chi tiết | Kết quả |
|---|---|---|---|---|
| **Thứ Hai** | Ngày 1 | Cơ bản CloudFormation | Viết YAML templates để tạo VPC và Subnets | Network stack được tạo thành công |
| **Thứ Ba** | Ngày 2 | Parameters & Outputs | Sửa code để tái sử dụng template cho nhiều môi trường (Dev/Prod) | Dynamic parameters hoạt động tốt |
| **Thứ Tư** | Ngày 3 | Cài đặt AWS CDK | Khởi tạo project AWS CDK bằng ngôn ngữ TypeScript | Hoàn thành bootstrap CDK trên tài khoản AWS |
| **Thứ Năm** | Ngày 4 | CDK Constructs | Sử dụng CDK L3 constructs để deploy ECS Fargate | Hạ tầng phức tạp được deploy chỉ với 50 dòng code |
| **Thứ Sáu** | Ngày 5 | Cập nhật Stacks | Thực hành phát hiện trôi dạt (Drift), update và rollback stack | Hiểu cách IaC quản lý state |

## 3. Kỹ năng công nghệ học được

| Công nghệ | Kiến thức đạt được |
|---|---|
| **AWS CloudFormation** | Stacks, Templates, Parameters, Resources, Outputs |
| **AWS CDK** | TypeScript, L1/L2/L3 Constructs, Synth, Deploy |

## 4. Thử thách & Giải pháp

| Thử thách | Giải pháp |
|---|---|
| **Lỗi tham chiếu vòng (Circular Dependency)** | Giải quyết lỗi tham chiếu vòng giữa 2 Security Groups trong CloudFormation bằng cách tách riêng ingress rules |

## 5. Phản ngẫm hàng tuần (Reflection)

| Hạng mục | Mô tả |
|---|---|
| **Kết quả học tập** | Nhận ra sức mạnh khổng lồ của việc quản lý hạ tầng bằng code |
| **Điểm cần cải thiện** | Học cách viết Custom Resources trong CDK |
| **Bước tiếp theo** | Thiết lập CI/CD pipeline để tự động hóa việc deploy IaC |
