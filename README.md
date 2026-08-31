# Terraform AWS EC2

This project demonstrates how to use **Terraform** to provision an **Amazon EC2 instance** using Infrastructure as Code (IaC).

## Technologies Used

* Terraform
* AWS EC2
* AWS CLI

## Project Files

* `main.tf` — Terraform configuration for creating the EC2 instance.
* `.terraform.lock.hcl` — Locks the Terraform provider version and dependencies.

## How It Works

1. Configure AWS credentials using AWS CLI.
2. Initialize Terraform using `terraform init`.
3. Review the infrastructure using `terraform plan`.
4. Create the EC2 instance using `terraform apply`.
5. terraform validate - Checks Terraform configuration syntax and ensures the configuration is valid.

## Result

An EC2 instance is provisioned in AWS through Terraform instead of creating it manually through the AWS Console.

## Security

AWS credentials and Terraform state files are not included in this repository.
