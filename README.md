# AWS EC2 Deployment using CloudFormation

## Project Overview
This project demonstrates Infrastructure as Code (IaC) using AWS CloudFormation to automate the provisioning of an EC2 instance with a fully configured Apache web server.

## Tech Stack
- AWS CloudFormation (YAML)
- Amazon EC2 (t3.micro)
- Amazon Linux 2023 AMI
- AWS Systems Manager (SSM Parameter Store)
- Security Groups
- Apache HTTP Server

## Key Features
- Automated infrastructure provisioning using CloudFormation
- Dynamic AMI retrieval via SSM Parameter Store
- Secure access with configured Security Groups (SSH & HTTP)
- Automated Apache setup using EC2 UserData scripts
- Outputs for public IP and website URL

## Architecture
User → Internet → Security Group → EC2 Instance → Apache Web Server

## Why This Project Matters
This project highlights how manual cloud setup can be transformed into automated, repeatable deployments using Infrastructure as Code, improving scalability, consistency, and deployment speed.

## Deployment Steps
1. Open AWS CloudFormation Console
2. Click "Create Stack" → "With new resources"
3. Upload `updated_aws.yaml`
4. Enter stack name
5. Select EC2 KeyPair
6. Launch stack

## Outputs
- EC2 instance successfully provisioned
- Apache web server automatically configured
- Accessible via public IP


## Screenshots
<img width="2559" height="1323" alt="Screenshot 2026-04-02 182637" src="https://github.com/user-attachments/assets/093f521d-324b-444f-b8a2-0c8f172f40d9" />
<img width="2552" height="1325" alt="Screenshot 2026-04-02 182721" src="https://github.com/user-attachments/assets/4cd17563-9ee3-473e-b3b5-123f2b7adf0a" />
<img width="2559" height="1436" alt="Screenshot 2026-04-02 183050" src="https://github.com/user-attachments/assets/92646f73-3946-42dc-81fb-3dcdd29c4e67" />


## Learning Outcome
- Hands-on experience with Infrastructure as Code
- Automated cloud resource provisioning
- Understanding EC2 networking and security




