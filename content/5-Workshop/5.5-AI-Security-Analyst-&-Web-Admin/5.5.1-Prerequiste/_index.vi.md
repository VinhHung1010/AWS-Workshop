---
title : "Các bước chuẩn bị"
date : 2024-01-01 
weight : 1
chapter : false
pre : " <b> 5.5.1. </b> "
---

### Chuẩn bị hạ tầng mạng

#### Khởi tạo VPC

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/$3.png)

#### Khởi tạo public subnet và private subnet

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/-1$3.png)

#### Khởi tạo internet gateways

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/-2$3.png)

#### Khởi tạo NAT gateway

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/-3$3.png)

#### Khởi tạo Route Table

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/-4$3.png)

### Chuẩn bị máy chủ EC2

#### Khởi tạo hai EC2 Instance:

Bastion Host (Public Subnet)

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/-5$3.png)

AI Server (Private Subnet)

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/-6$3.png)

### Chuẩn bị Security Group

Cấu hình Security Group cho các EC2.

Bastion Host (Public Subnet)

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/-8$3.png)

AI Server (Private Subnet)

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/-7$3.png)

### Chuẩn bị IAM Role

Tạo IAM Role

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/-9$3.png)


