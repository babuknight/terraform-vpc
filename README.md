# Terraform VPC Setup

This Terraform project sets up a basic AWS infrastructure with:

- ✅ A custom VPC
- ✅ One public and one private subnet
- ✅ An Internet Gateway
- ✅ A NAT Gateway (with Elastic IP)
- ✅ Route Tables
- ✅ A security group for SSH/HTTP
- ✅ EC2 instances in both public and private subnets

## How to Use

1. Configure your AWS CLI with `aws configure`
2. Run the following Terraform commands:

```bash
terraform init
terraform apply
```

## Notes

- Replace the AMI ID with a valid one for your AWS region
- Default region used: `us-east-1`