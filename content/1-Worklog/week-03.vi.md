---
title: "Tuần 03: Máy tính (EC2 & Auto Scaling)"
weight: 3
---

## 1. Tóm tắt tuần

| Hạng mục | Mô tả |
|---|---|
| **Tuần** | Tuần 03 |
| **Chủ đề** | Amazon EC2, Application Load Balancers, và Auto Scaling Groups |
| **Mục tiêu chính** | Tính sẵn sàng cao, loại instance, AMIs, và script user data |

## 2. Nhật ký công việc hàng ngày

| Ngày | Kế hoạch | Tác vụ chính | Hoạt động chi tiết | Kết quả |
|---|---|---|---|---|
| **Thứ Hai** | Ngày 1 | Triển khai EC2 | Khởi tạo EC2 với nhiều loại AMI và instance types khác nhau | Instances chạy thành công |
| **Thứ Ba** | Ngày 2 | User Data Scripts | Tự động cài đặt Apache web server thông qua user data | Web server tự động chạy khi boot |
| **Thứ Tư** | Ngày 3 | Custom AMIs | Tạo 'Golden AMI' với các thư viện cài sẵn | Golden AMI sẵn sàng để Auto Scaling |
| **Thứ Năm** | Ngày 4 | Application Load Balancer | Cấu hình ALB và Target Groups | Traffic được phân phối đều giữa các EC2 |
| **Thứ Sáu** | Ngày 5 | Auto Scaling Group | Gắn ASG vào ALB với chính sách scale theo CPU | Hệ thống tự động co giãn thành công |

## 3. Kỹ năng công nghệ học được

| Công nghệ | Kiến thức đạt được |
|---|---|
| **Amazon EC2** | Các dòng EC2, AMIs, User Data, kết nối ổ cứng EBS |
| **Elastic Load Balancing** | Cấu hình Listener, Rules, và Health checks |
| **Auto Scaling** | Launch templates và chính sách scale động |

## 4. Thử thách & Giải pháp

| Thử thách | Giải pháp |
|---|---|
| **Lỗi Health Check ALB** | Đổi đường dẫn health check từ / thành /index.html và mở port 80 trên SG |

## 5. Phản ngẫm hàng tuần (Reflection)

| Hạng mục | Mô tả |
|---|---|
| **Kết quả học tập** | Xây dựng thành công kiến trúc web tự động co giãn và tính sẵn sàng cao |
| **Điểm cần cải thiện** | Phân tích và tối ưu chi phí khi chọn loại EC2 instance |
| **Bước tiếp theo** | Tích hợp các giải pháp lưu trữ mở rộng (S3, EFS) |
