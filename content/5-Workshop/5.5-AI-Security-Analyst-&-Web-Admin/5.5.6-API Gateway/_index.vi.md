---
title : "Cấu hình Amazon API Gateway"
date : 2024-01-01
weight : 6
chapter : false
pre : " <b> 5.5.6 </b> "
---

### Giới thiệu

- Trong phần này, bạn sẽ tạo và cấu hình Amazon API Gateway để cung cấp một API công khai cho ứng dụng React. API Gateway tiếp nhận URL từ giao diện người dùng, chuyển yêu cầu đến AWS Lambda và trả kết quả phân tích từ mô hình AI về lại cho ứng dụng.

### Truy cập Amazon API Gatewway

- Chọn create API

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/$3.png)

### Tạo HTTP API 

- Chọn **build -> Nhập tên API -> Review and create -> Create**

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/-1$3.png)

### Tạo Integration với AWS Lambda

- Điền thông tin liên kết với Lambda

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/-2$3.png)

- API Gateway được liên kết với Lambda Function

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/-3$3.png)

### Tạo Route cho API

- Chọn **route -> create**

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/-4$3.png)

### Cấu hình CORS

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/-5$3.png)

### Kiểm tra Stage

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/-6$3.png)

### Kiểm tra API Gateway

- Kiểm tra trên postman

- Nhập đường link **https://lqlv4r23xe.execute-api.ap-southeast-1.amazonaws.com/dev/analyze-url**

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/-7$3.png)

- postman trả thông số như trên hình là thành công