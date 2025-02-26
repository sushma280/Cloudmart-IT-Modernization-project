# Cloudmart IT Modernization Project

**Project Overview**
CloudMart, a leading e-commerce company, is facing growing challenges with IT inefficiencies and rising customer support costs. The company is losing its competitive edge to Klarna, which offers similar products at lower prices while leveraging modern cloud infrastructure and AI-driven automation.
To regain its market position, CloudMart’s CTO has initiated a digital transformation project aimed at rearchitecting and migrating its application to a modern cloud-based infrastructure. This initiative integrates MultiCloud, DevOps, and AI automation to enhance IT efficiency, scalability, and customer experience.

As part of this transformation, we are participating in a 5-day hands-on challenge to deploy CloudMart’s IT infrastructure using modern cloud and DevOps practices. 

![Screenshot 2025-02-25 120721](https://github.com/user-attachments/assets/89070bd3-5617-4377-9591-7ece3b162093)

**Day 1**

On Day 1, I worked on setting up Terraform using Claude as an AI assistant. I created an S3 bucket and DynamoDB tables, launched an EC2 instance, and configured IAM roles for managing AWS resources.

**Resources Used**:
AWS Services: S3, EC2, IAM, DynamoDB
Tools & Technologies: Terraform, AWS CLI, Claude AI

**Steps Performed**:
1. Used Claude AI to Generate Terraform Code : Generated Terraform code for an S3 bucket
2. Created an IAM Role for EC2 : Created an IAM role named EC2Admin with AdministratorAccess attached.
3. Launched an EC2 Instance :

   -> Used Amazon Linux 2 AMI

   -> Attached the EC2Admin IAM role

   -> Enabled SSH access
5. Installed Terraform on EC2 Instance
6. Created and Applied Terraform Configuration
7. Created DynamoDB Tables for CloudMart

Set up Terraform, launched an EC2 instance, installed Terraform, and created AWS resources (S3, DynamoDB). 

Day 1 was focused on infrastructure automation using Terraform and AI-driven assistance.



