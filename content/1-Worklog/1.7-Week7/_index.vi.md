---
title: "WEEK 7 WORKLOG"
date: "2026-05-29"
weight: 7
chapter: false
pre: " <b> 1.7 </b> "
---

### **Week 7 Objectives**

* Tìm hiểu và triển khai kiến trúc Serverless (phi máy chủ) bằng **AWS Lambda** và **API Gateway**.
* Viết template CloudFormation để tự động hóa việc triển khai hàm Lambda và endpoint API.
* Tìm hiểu tính năng nâng cao của CloudFormation: **StackSets**, để triển khai tài nguyên (S3) đồng bộ trên nhiều tài khoản và region.
* Bắt đầu tìm hiểu một công cụ IaC mới: **Terraform** (HCL syntax).
* Thực hành các lệnh cơ bản của Terraform (`init`, `plan`, `apply`) và học cách quản lý cấu hình bằng **biến (variables)** và file `.tfvars`.

---

### **Tasks to be carried out this week**

| Day | Task | Start Date | Completion Date | Reference/Material |
| :--- | :--- | :--- | :--- | :--- |
| 1 (Thứ Hai) | **Tìm hiểu Serverless**: Học về AWS Lambda, viết template CloudFormation (tạo IAM Role, Lambda Function) và tích hợp API Gateway. | 12/06/2026 | 12/06/2026 |https://youtu.be/eP_cB6SZQ1Q?si=-hcmw4BEQQ4fHEln |
| 2 (Thứ Ba) | **CloudFormation StackSets**: Tìm hiểu StackSets, viết template (tạo S3) và deploy StackSet ra nhiều tài khoản/region. | 15/06/2026 | 15/06/2026 |https://youtu.be/K2Qzwym2Z6k?si=jcB7INEokBx0jQEK |
| 3 (Thứ Tư) | **Bắt đầu với Terraform**: Viết file `main.tf` đầu tiên (khai báo provider "aws", resource "aws_s3_bucket"). Chạy `terraform init` và `plan`. | 16/06/2026 | 16/06/2026 | |
| 4 (Thứ Năm) | **Hoàn thiện & Dọn dẹp (CloudFormation)**: Triển khai, kiểm tra (SSH/HTTP) một stack hoàn chỉnh (VPC+EC2) và học cách xóa stack (`delete-stack`). | 17/06/2026 | 17/06/2026 | |
| 5 (Thứ Sáu) | **Hoàn thành Terraform**: Chạy `terraform apply` để tạo S3 bucket. Học cách dùng **variables** và file `.tfvars` để quản lý tên bucket. | 18/06/2026 | 18/06/2026 | |

---

### **Week 7 Achievements**

* Nắm vững Serverless, triển khai Lambda với CloudFormation.
* Tích hợp Lambda với API Gateway để tạo endpoint công khai.
* Triển khai StackSets trên nhiều tài khoản AWS.
* Quản lý Terraform variables và file .tfvars.

