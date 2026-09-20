---
title: "Tuần 10: Bảo mật & Tuân thủ"
weight: 10
---

## 1. Tóm tắt tuần

| Hạng mục | Mô tả |
|---|---|
| **Tuần** | Tuần 10 |
| **Chủ đề** | AWS KMS, AWS WAF, Amazon GuardDuty, và AWS Config |
| **Mục tiêu chính** | Mã hóa dữ liệu, phát hiện mối đe dọa, tường lửa web, kiểm toán tuân thủ |

## 2. Nhật ký công việc hàng ngày

| Ngày | Kế hoạch | Tác vụ chính | Hoạt động chi tiết | Kết quả |
|---|---|---|---|---|
| **Thứ Hai** | Ngày 1 | AWS KMS | Tạo CMKs và bắt buộc mã hóa S3 buckets và ổ EBS | Dữ liệu ở trạng thái nghỉ (Data at rest) đã được mã hóa |
| **Thứ Ba** | Ngày 2 | AWS Certificate Manager | Xin cấp chứng chỉ SSL/TLS và gắn vào Application Load Balancer | Dữ liệu trên đường truyền được mã hóa (HTTPS) |
| **Thứ Tư** | Ngày 3 | AWS WAF | Gắn Tường lửa WAF vào ALB để chặn SQL Injection và XSS | Ứng dụng được bảo vệ khỏi các lỗ hổng web phổ biến |
| **Thứ Năm** | Ngày 4 | Amazon GuardDuty | Bật GuardDuty để dò tìm các mối đe dọa thông minh | Bắt đầu giám sát các hoạt động từ IP độc hại |
| **Thứ Sáu** | Ngày 5 | AWS Config | Thiết lập Config rule để đảm bảo không có S3 bucket nào bị Public | Hệ thống theo dõi tuân thủ (Compliance) liên tục hoạt động |

## 3. Kỹ năng công nghệ học được

| Công nghệ | Kiến thức đạt được |
|---|---|
| **AWS KMS** | Khóa đối xứng/bất đối xứng, Envelope Encryption (Mã hóa phong bì) |
| **AWS WAF** | Web ACLs, Managed rule groups (Bộ quy tắc có sẵn) |
| **AWS Config & GuardDuty** | Kiểm toán liên tục và phát hiện mối đe dọa bằng AI |

## 4. Thử thách & Giải pháp

| Thử thách | Giải pháp |
|---|---|
| **WAF chặn nhầm người dùng thật** | WAF báo False Positive chặn mất API. Giải quyết bằng cách chỉnh mức độ ưu tiên rule và cấu hình whitelist IP |

## 5. Phản ngẫm hàng tuần (Reflection)

| Hạng mục | Mô tả |
|---|---|
| **Kết quả học tập** | Biết cách triển khai bảo mật đa tầng (Defense in Depth) trên kiến trúc AWS |
| **Điểm cần cải thiện** | Tự động hóa xử lý vi phạm AWS Config bằng Systems Manager Automation |
| **Bước tiếp theo** | Triển khai giải pháp giám sát và ghi log toàn diện |
