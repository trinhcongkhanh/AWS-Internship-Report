---
title: "Tuần 11: Giám sát, Ghi Log & Khả năng quan sát"
weight: 11
---

## 1. Tóm tắt tuần

| Hạng mục | Mô tả |
|---|---|
| **Tuần** | Tuần 11 |
| **Chủ đề** | Amazon CloudWatch, AWS CloudTrail, và AWS X-Ray |
| **Mục tiêu chính** | Metrics, Cảnh báo (Alarms), phân tích Logs, và distributed tracing |

## 2. Nhật ký công việc hàng ngày

| Ngày | Kế hoạch | Tác vụ chính | Hoạt động chi tiết | Kết quả |
|---|---|---|---|---|
| **Thứ Hai** | Ngày 1 | CloudWatch Metrics & Alarms | Tạo dashboard tùy chỉnh và các cảnh báo về CPU/RAM | Cảnh báo tự động gửi qua email qua SNS |
| **Thứ Ba** | Ngày 2 | CloudWatch Logs | Cài đặt CloudWatch Agent trên EC2 để gom application log | Hệ thống Log tập trung hoàn thành |
| **Thứ Tư** | Ngày 3 | AWS CloudTrail | Bật trail đa khu vực (multi-region) và phân tích lịch sử API | Có sẵn Log kiểm toán cho mọi hoạt động trong tài khoản AWS |
| **Thứ Năm** | Ngày 4 | CloudWatch Log Insights | Viết câu lệnh truy vấn log JSON để tìm nguyên nhân gây lỗi 500 | Tốc độ gỡ lỗi log được tăng cường |
| **Thứ Sáu** | Ngày 5 | AWS X-Ray | Tích hợp thư viện X-Ray vào app Node.js để theo dõi luồng request từ API Gateway -> Lambda -> DynamoDB | Mô phỏng bản đồ dịch vụ (Service Map) thành công |

## 3. Kỹ năng công nghệ học được

| Công nghệ | Kiến thức đạt được |
|---|---|
| **Amazon CloudWatch** | Dashboards, Cảnh báo (Alarms), Logs, Log Insights |
| **AWS CloudTrail** | Kiểm toán API (API auditing), Event history |
| **AWS X-Ray** | Service maps, Phân tích luồng (Trace analysis) |

## 4. Thử thách & Giải pháp

| Thử thách | Giải pháp |
|---|---|
| **Chi phí lưu Log quá cao** | Cấu hình chính sách giữ log (retention) giảm xuống 30 ngày và tự động export log cũ sang S3 Glacier |

## 5. Phản ngẫm hàng tuần (Reflection)

| Hạng mục | Mô tả |
|---|---|
| **Kết quả học tập** | Sử dụng thành thạo các công cụ giám sát để phát hiện và gỡ lỗi nhanh chóng |
| **Điểm cần cải thiện** | Tạo các CloudWatch Metric Filters phức tạp hơn cho các chỉ số doanh thu (business metrics) |
| **Bước tiếp theo** | Tích hợp dự án cuối khóa và Đánh giá kiến trúc tổng thể |
