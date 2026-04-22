# aws-ec2-cloudformation-project
# 🚀 AWS EC2 Deployment using CloudFormation

## 📌 Project Overview
This project demonstrates Infrastructure as Code (IaC) using AWS CloudFormation to automatically provision an EC2 instance with a web server.

## 🛠️ Tech Stack
- AWS CloudFormation (YAML)
- Amazon EC2 (t3.micro)
- Amazon Linux 2023 AMI
- Security Groups
- Apache HTTP Server

## ⚙️ Features
- Automated EC2 instance provisioning
- Dynamic AMI retrieval using AWS SSM Parameter Store
- Secure access via SSH (Port 22) and HTTP (Port 80)
- Auto-configured Apache web server using UserData
- Outputs public IP and website URL

## 🚀 Deployment Steps
1. Go to AWS CloudFormation Console
2. Click **Create Stack**
3. Upload `template.yaml`
4. Select your EC2 KeyPair
5. Launch stack

## 🌐 Output
Once deployed:
- EC2 instance is created
- Web server starts automatically
- Access via public URL
