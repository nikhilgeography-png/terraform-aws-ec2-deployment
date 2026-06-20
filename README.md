Terraform AWS EC2 Deployment

Project Overview

This project uses Terraform to provision AWS infrastructure, including:

- AWS EC2 Instance
- Security Group Configuration
- Infrastructure as Code (IaC)

Technologies Used

- Terraform
- AWS EC2
- AWS Security Groups
- GitHub

Project Structure

terraform-aws-ec2-deployment/

├── main.tf

├── terraform-sg/

│ └── main.tf

└── .gitignore

Deployment Steps

1. Initialize Terraform

terraform init

2. Validate Configuration

terraform validate

3. Preview Infrastructure

terraform plan

4. Deploy Infrastructure

terraform apply

Resources Created

- EC2 Instance
- Security Group
- SSH Access (Port 22)
- Application Port (8080)

Author

Nikhil More

DevOps & Cloud Engineer
