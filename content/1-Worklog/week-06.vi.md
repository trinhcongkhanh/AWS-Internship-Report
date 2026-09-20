---
title: "Tuần 06: Điện toán không máy chủ (Serverless)"
weight: 6
---

## 1. Tóm tắt tuần

| Hạng mục | Mô tả |
|---|---|
| **Tuần** | Tuần 06 |
| **Chủ đề** | AWS Lambda, API Gateway, và Kiến trúc hướng sự kiện (Event-driven) |
| **Mục tiêu chính** | Microservices, Serverless functions, triggers, và thiết kế API |

## 2. Nhật ký công việc hàng ngày

| Ngày | Kế hoạch | Tác vụ chính | Hoạt động chi tiết | Kết quả |
|---|---|---|---|---|
| **Thứ Hai** | Ngày 1 | Lambda Functions | Viết và deploy các hàm Lambda bằng Python | Functions chạy thành công |
| **Thứ Ba** | Ngày 2 | API Gateway | Tạo REST APIs và tích hợp với Lambda | Gọi API endpoints thành công |
| **Thứ Tư** | Ngày 3 | Event Triggers | Cấu hình S3 kích hoạt Lambda mỗi khi có file mới tải lên | Tự động hóa xử lý hình ảnh |
| **Thứ Năm** | Ngày 4 | DynamoDB Streams | Xử lý event từ DynamoDB stream bằng Lambda | Đồng bộ dữ liệu real-time thành công |
| **Thứ Sáu** | Ngày 5 | Serverless Framework / SAM | Đóng gói và deploy ứng dụng serverless bằng AWS SAM | Hạ tầng được deploy qua code (IaC) |

## 3. Kỹ năng công nghệ học được

| Công nghệ | Kiến thức đạt được |
|---|---|
| **AWS Lambda** | Điện toán Serverless, Execution Roles, Environment Variables |
| **Amazon API Gateway** | RESTful APIs, Stages, Deployments, Custom Domains |
| **AWS SAM** | Serverless Application Model templates |

## 4. Thử thách & Giải pháp

| Thử thách | Giải pháp |
|---|---|
| **Độ trễ Cold Start của Lambda** | Tối ưu hóa kích thước package và dung lượng RAM để giảm latency cold start |

## 5. Phản ngẫm hàng tuần (Reflection)

| Hạng mục | Mô tả |
|---|---|
| **Kết quả học tập** | Chuyển đổi tư duy từ kiến trúc server truyền thống sang event-driven |
| **Điểm cần cải thiện** | Cần tìm hiểu cách tracking và giám sát hệ thống serverless phức tạp (AWS X-Ray) |
| **Bước tiếp theo** | Học về Containerization (Docker, ECS) cho các ứng dụng chạy nền liên tục |
