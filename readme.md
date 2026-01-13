# AWS Infrastructure Automation with Terraform 🚀

This project demonstrates how to build a production-ready, highly available network on AWS using Infrastructure as Code (IaC).

## 🏗️ Architecture
- **VPC:** Custom VPC with `10.0.0.0/16` CIDR.
- **Subnets:** 2 Public Subnets in different Availability Zones (`us-east-1a` & `us-east-1b`) for High Availability.
- **Connectivity:** Internet Gateway attached to a Public Route Table.
- **Security:** Security Group allowing SSH (Port 22) and HTTP (Port 80) traffic.
- **Compute:** Ubuntu EC2 Instance deployed in a public subnet with auto-assigned Public IP.

## 🛠️ Tools Used
- **Terraform** for Provisioning.
- **AWS CLI** for Authentication.
- **GitHub CLI** for Version Control.

## 🚀 How to Run
1. `terraform init`
2. `terraform plan`
3. `terraform apply --auto-approve`
