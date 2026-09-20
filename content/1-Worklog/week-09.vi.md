---
title: "Tuần 09: CI/CD Pipelines"
weight: 9
---

## 1. Tóm tắt tuần

| Hạng mục | Mô tả |
|---|---|
| **Tuần** | Tuần 09 |
| **Chủ đề** | AWS CodeCommit, CodeBuild, CodeDeploy, và CodePipeline |
| **Mục tiêu chính** | Tích hợp liên tục (CI), Triển khai liên tục (CD), và tự động hóa build |

## 2. Nhật ký công việc hàng ngày

| Ngày | Kế hoạch | Tác vụ chính | Hoạt động chi tiết | Kết quả |
|---|---|---|---|---|
| **Thứ Hai** | Ngày 1 | Quản lý mã nguồn | Đưa code lên AWS CodeCommit repositories | Repositories được phân quyền bảo mật qua IAM |
| **Thứ Ba** | Ngày 2 | AWS CodeBuild | Tạo file buildspec.yml để biên dịch code và chạy unit test | Unit test tự động pass trên CodeBuild |
| **Thứ Tư** | Ngày 3 | Docker trong CodeBuild | Cập nhật buildspec để tự build và push Docker images lên ECR | Image tự động push mỗi lần có commit mới |
| **Thứ Năm** | Ngày 4 | AWS CodeDeploy | Cấu hình Blue/Green deployment cho ECS Fargate | Sẵn sàng cơ chế deploy không gây gián đoạn (Zero-downtime) |
| **Thứ Sáu** | Ngày 5 | AWS CodePipeline | Nối các bước Source -> Build -> Deploy thành một Pipeline hoàn chỉnh | Hệ thống CI/CD hoàn toàn tự động đã hoạt động |

## 3. Kỹ năng công nghệ học được

| Công nghệ | Kiến thức đạt được |
|---|---|
| **AWS CodePipeline** | Điều phối pipeline, các stages (bước), và artifacts |
| **AWS CodeBuild** | File Buildspec, môi trường build |
| **AWS CodeDeploy** | Deployment groups, định tuyến Blue/Green |

## 4. Thử thách & Giải pháp

| Thử thách | Giải pháp |
|---|---|
| **Lỗi phân quyền IAM cho CodeBuild** | Quá trình build thất bại do thiếu quyền push lên ECR. Giải quyết bằng cách gán inline policy vào service role của CodeBuild |

## 5. Phản ngẫm hàng tuần (Reflection)

| Hạng mục | Mô tả |
|---|---|
| **Kết quả học tập** | Thành thạo tự động hóa quy trình deploy end-to-end trên AWS |
| **Điểm cần cải thiện** | Tích hợp các tool kiểm tra chất lượng code (như SonarQube) vào CodePipeline |
| **Bước tiếp theo** | Triển khai các biện pháp bảo mật và kiểm tra tuân thủ hệ thống |
