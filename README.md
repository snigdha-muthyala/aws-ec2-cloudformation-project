# AWS EC2 Deployment using CloudFormation

## Project Overview
This project demonstrates the use of Infrastructure as Code (IaC) with AWS CloudFormation to automate the provisioning of an EC2 instance along with a fully configured web server.

## Tech Stack
- AWS CloudFormation (YAML)
- Amazon EC2 (t3.micro)
- Amazon Linux 2023 AMI
- AWS Systems Manager (SSM Parameter Store)
- Security Groups
- Apache HTTP Server

## Key Features
- Automated EC2 instance provisioning
- Dynamic AMI retrieval using SSM Parameter Store
- Secure access via SSH (Port 22) and HTTP (Port 80)
- Auto-configured Apache web server using UserData
- Outputs public IP and website URL

## Architecture Flow
1. Deploy CloudFormation template
2. Create security group with inbound rules
3. Launch EC2 instance using latest Amazon Linux AMI
4. Execute UserData script to install Apache
5. Access application via public IP

## Deployment Steps
1. Go to AWS CloudFormation Console
2. Click "Create Stack" → "With new resources (standard)"
3. Upload the template.yaml file
4. Enter stack name
5. Select EC2 KeyPair
6. Launch stack

## Outputs
- EC2 instance running
- Apache web server active
- Accessible via public IP

