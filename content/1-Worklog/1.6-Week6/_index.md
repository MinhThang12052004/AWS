---
title: "WEEK 6 WORKLOG"
date: "2026-05-22"
weight: 6
chapter: false
pre: " <b> 1.6 </b> "
---

### **Week 6 Objectives**

* Take a deep dive into **Infrastructure as Code (IaC)** using **AWS CloudFormation**.
* Master YAML syntax and the structure of a CloudFormation Template (including `Parameters`, `Resources`, `Outputs`).
* Write templates to automate the creation of single resources (S3 Bucket) and a complex network (VPC, Subnet, IGW).
* Extend the template to automate the deployment of a full web server (EC2, Security Group).
* Master the stack lifecycle management process (create, update, delete) using the AWS Console and CLI.

---

### **Tasks to be carried out this week**

| Day | Task | Start Date | Completion Date | Reference/Material |
| :--- | :--- | :--- | :--- | :--- |
| 1 (Mon) | **Learn CloudFormation & YAML**: Study sections (Parameters, Resources) and YAML syntax. Write a simple S3 Bucket template. | 05/06/2026 | 05/06/2026 |https://000037.awsstudygroup.com/vi/1-introduce/ |
| 2 (Tue) | **Deploy Stack & Parameters**: Deploy the S3 stack. Add `Parameters` (e.g., custom bucket name) to the template and learn to update the stack. | 08/06/2026 | 08/06/2026 | |
| 3 (Wed) | **Write Network Template**: Write a new template for network infrastructure (VPC, Public Subnet, IGW, Route Table). Use `Outputs`. | 09/06/2026 | 09/06/2026 | |
| 4 (Thu) | **Write EC2 Template**: Extend the network template, adding `Resources` for a Security Group (SSH, HTTP) and an EC2 instance (specifying AMI). | 10/06/2026 | 10/06/2026 | |
| 5 (Fri) | **Deploy & Cleanup**: Deploy the complete stack (VPC + EC2). Test SSH/HTTP access. Learn to delete the stack (`aws cloudformation delete-stack`). | 11/06/2026 | 11/06/2026 | |

---

### **Week 6 Achievements**

* Mastered YAML and CloudFormation template structure with Parameters, Resources, and Outputs.
* Successfully deployed S3, VPC, and EC2 resources using CloudFormation templates.
* Proficiently used Parameters to customize resources at deployment time.
* Mastered stack lifecycle management: create, update, and delete operations.

