---
title: "Tuần 04: Các giải pháp lưu trữ"
weight: 4
---

## 1. Tóm tắt tuần

| Hạng mục | Mô tả |
|---|---|
| **Tuần** | Tuần 04 |
| **Chủ đề** | Các dịch vụ lưu trữ AWS: S3, EBS, và EFS |
| **Mục tiêu chính** | Object storage, block storage, hệ thống file chia sẻ, chính sách vòng đời (lifecycle) |

## 2. Nhật ký công việc hàng ngày

| Ngày | Kế hoạch | Tác vụ chính | Hoạt động chi tiết | Kết quả |
|---|---|---|---|---|
| **Thứ Hai** | Ngày 1 | Cơ bản về S3 | Tạo buckets, bật versioning và mã hóa SSE | Bucket được tạo và bảo mật |
| **Thứ Ba** | Ngày 2 | S3 Lifecycle Rules | Cấu hình chuyển data cũ sang S3 Glacier | Tối ưu hóa chi phí lưu trữ S3 |
| **Thứ Tư** | Ngày 3 | Ổ cứng EBS | Tạo, gắn, và tăng dung lượng EBS trên EC2 đang chạy | Tăng dung lượng không cần downtime |
| **Thứ Năm** | Ngày 4 | EBS Snapshots | Tự động hóa sao lưu EBS hàng ngày bằng Data Lifecycle Manager | Chiến lược backup hoàn thiện |
| **Thứ Sáu** | Ngày 5 | Amazon EFS | Mount EFS cho nhiều EC2 ở các AZ khác nhau | Hệ thống chia sẻ file hoạt động tốt |

## 3. Kỹ năng công nghệ học được

| Công nghệ | Kiến thức đạt được |
|---|---|
| **Amazon S3** | Buckets, Objects, Versioning, Storage Classes, Lifecycle |
| **Amazon EBS** | Các loại ổ cứng (gp3, io2), Snapshots, DLM |
| **Amazon EFS** | Mount NFS, chia sẻ file liên Availability Zone (AZ) |

## 4. Thử thách & Giải pháp

| Thử thách | Giải pháp |
|---|---|
| **Lỗi Timeout khi mount EFS** | Giải quyết bằng cách mở port NFS (2049) trên Security Group của EFS |

## 5. Phản ngẫm hàng tuần (Reflection)

| Hạng mục | Mô tả |
|---|---|
| **Kết quả học tập** | Phân biệt rõ ràng ứng dụng của Block storage, File storage, và Object storage |
| **Điểm cần cải thiện** | Tìm hiểu thêm về S3 Replication cho Disaster Recovery (DR) |
| **Bước tiếp theo** | Triển khai cơ sở dữ liệu (Database) để tách biệt state và compute |
