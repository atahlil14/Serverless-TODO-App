# 📝 Serverless TODO App (AWS Project)

This is a serverless TODO list app built on AWS using Lambda, API Gateway, and DynamoDB. It’s designed to showcase scalable, backendless architecture while keeping everything cost-effective and fast.

## 🚀 Features
- Create, update, delete, and retrieve tasks
- Fully serverless (no EC2 or servers)
- DynamoDB stores all task data
- Secure and scalable API endpoints
- Optional: Auth with Amazon Cognito

## ☁️ AWS Services Used
- AWS Lambda
- Amazon API Gateway
- Amazon DynamoDB
- (Optional) Amazon Cognito
- (Optional) Amazon S3 for frontend

## 🔧 Architecture Diagram
![Architecture](./architecture.png)

## 🧱 Folder Structure

```bash
lambda/           # Backend logic
terraform/        # Infrastructure as Code (optional)
README.md         # Project overview
architecture.png  # AWS architecture diagram
