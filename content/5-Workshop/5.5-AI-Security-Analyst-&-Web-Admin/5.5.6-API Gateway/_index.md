---
title : "Configure Amazon API Gateway"
date : 2024-01-01
weight : 6
chapter : false
pre : " <b> 5.5.6 </b> "
---

### Introduction

- In this section, you will create and configure Amazon API Gateway to provide a public API for the React application. API Gateway receives URLs from the user interface, forwards requests to AWS Lambda, and returns analysis results from the AI model back to the application.

### Access Amazon API Gateway

- Select create API

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/$3.png)

### Create HTTP API 

- Select **build -> Enter API name -> Review and create -> Create**

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/-1$3.png)

### Create Integration with AWS Lambda

- Fill in the information to link with Lambda

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/-2$3.png)

- API Gateway is linked with Lambda Function

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/-3$3.png)

### Create Route for API

- Select **route -> create**

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/-4$3.png)

### Configure CORS

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/-5$3.png)

### Check Stage

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/-6$3.png)

### Test API Gateway

- Test on Postman

- Enter the URL **https://lqlv4r23xe.execute-api.ap-southeast-1.amazonaws.com/dev/analyze-url**

![alt text](/AWS-Workshop/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.6-API Gateway/-7$3.png)

- Postman returns the parameters as shown in the figure, which means success
