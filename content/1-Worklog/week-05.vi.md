---
title: "Tuần 05: Cơ sở dữ liệu (RDS & DynamoDB)"
weight: 5
---

## 1. Tóm tắt tuần

| Hạng mục | Mô tả |
|---|---|
| **Tuần** | Tuần 05 |
| **Chủ đề** | Relational (SQL) và NoSQL Databases trên AWS |
| **Mục tiêu chính** | Amazon RDS, triển khai Multi-AZ, Read Replicas, Amazon DynamoDB |

## 2. Nhật ký công việc hàng ngày

| Ngày | Kế hoạch | Tác vụ chính | Hoạt động chi tiết | Kết quả |
|---|---|---|---|---|
| **Thứ Hai** | Ngày 1 | Triển khai RDS | Tạo instance MySQL RDS trong private subnet | Database chạy an toàn trong mạng nội bộ |
| **Thứ Ba** | Ngày 2 | Multi-AZ & Backups | Bật tính năng Multi-AZ để đảm bảo HA và tự động backup | Kiến trúc DB chống chịu lỗi |
| **Thứ Tư** | Ngày 3 | Read Replicas | Tạo Read Replica để giảm tải các query phân tích | Hiệu năng đọc (Read) được cải thiện |
| **Thứ Năm** | Ngày 4 | Cơ bản DynamoDB | Tạo bảng NoSQL và định nghĩa Partition/Sort keys | Bảng DynamoDB sẵn sàng |
| **Thứ Sáu** | Ngày 5 | Tích hợp Ứng dụng | Kết nối app Python tới cả RDS và DynamoDB | App truy vấn dữ liệu thành công |

## 3. Kỹ năng công nghệ học được

| Công nghệ | Kiến thức đạt được |
|---|---|
| **Amazon RDS** | Quản lý CSDL quan hệ, Multi-AZ, Backups, Parameter Groups |
| **Amazon DynamoDB** | NoSQL, Partition Keys, Các chế độ Capacity (On-Demand vs Provisioned) |

## 4. Thử thách & Giải pháp

| Thử thách | Giải pháp |
|---|---|
| **Vấn đề 'Hot Partitions' trên DynamoDB** | Thiết kế lại partition key bằng composite ID để phân tán đều lưu lượng R/W |

## 5. Phản ngẫm hàng tuần (Reflection)

| Hạng mục | Mô tả |
|---|---|
| **Kết quả học tập** | Nắm vững cách setup managed database và mô hình dữ liệu NoSQL |
| **Điểm cần cải thiện** | Cần tìm hiểu sâu hơn về Global Secondary Indexes (GSIs) của DynamoDB |
| **Bước tiếp theo** | Dịch chuyển ứng dụng Monolithic sang kiến trúc Serverless |
