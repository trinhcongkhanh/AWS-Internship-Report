---
title: "Tuần 02: VPC & Mạng (Networking)"
weight: 2
---

## 1. Tóm tắt tuần

| Hạng mục | Mô tả |
|---|---|
| **Tuần** | Tuần 02 |
| **Chủ đề** | Thiết kế Virtual Private Cloud (VPC) và Định tuyến mạng |
| **Mục tiêu chính** | Public/Private subnets, NAT Gateways, Route Tables, Security Groups |

## 2. Nhật ký công việc hàng ngày

| Ngày | Kế hoạch | Tác vụ chính | Hoạt động chi tiết | Kết quả |
|---|---|---|---|---|
| **Thứ Hai** | Ngày 1 | Kiến trúc VPC | Thiết kế kiến trúc mạng VPC 3 lớp | Sơ đồ kiến trúc được duyệt |
| **Thứ Ba** | Ngày 2 | Subnets & Routing | Tạo public/private subnet và gắn Internet Gateway | Định tuyến cơ bản hoạt động |
| **Thứ Tư** | Ngày 3 | NAT Gateway | Cấu hình NAT Gateway cho subnet nội bộ | Server nội bộ có thể cập nhật HĐH |
| **Thứ Năm** | Ngày 4 | Security Groups & NACLs | Cấu hình tường lửa stateful và stateless | Mạng được cô lập và bảo mật |
| **Thứ Sáu** | Ngày 5 | VPC Peering | Kiểm thử kết nối peering giữa 2 môi trường VPC | Kết nối liên VPC thành công |

## 3. Kỹ năng công nghệ học được

| Công nghệ | Kiến thức đạt được |
|---|---|
| **Amazon VPC** | Chia mạng con (Subnetting), CIDR, Route Tables |
| **Bảo mật Mạng** | Phân biệt Security Groups và Network ACLs |

## 4. Thử thách & Giải pháp

| Thử thách | Giải pháp |
|---|---|
| **Định tuyến bất đối xứng** | Sửa Route Tables để đảm bảo luồng traffic trả về đi đúng hướng |

## 5. Phản ngẫm hàng tuần (Reflection)

| Hạng mục | Mô tả |
|---|---|
| **Kết quả học tập** | Hiểu sâu hơn về mạng đám mây và tính toán CIDR |
| **Điểm cần cải thiện** | Tìm hiểu thêm về các mô hình định tuyến nâng cao như Transit Gateway |
| **Bước tiếp theo** | Triển khai tài nguyên máy chủ vào trong mạng VPC vừa tạo |
