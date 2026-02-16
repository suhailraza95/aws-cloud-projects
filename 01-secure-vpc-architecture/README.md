
# Secure Multi-Tier VPC Architecture

## 📌 Objective
Design a secure AWS network architecture using public and private subnets
with controlled access to resources.

## 🏗️ Architecture
- Custom VPC
- Public subnet with Bastion Host
- Private subnet with EC2
- NAT Gateway for outbound access
- Internet Gateway
- Route tables for traffic control

## 🔐 Security Implementation
- SSH access only via Bastion Host
- Private EC2 has no public IP
- Least-privilege Security Groups
- Controlled inbound and outbound rules

## ✅ Validation
- SSH into Bastion Host
- Access private EC2 from Bastion
- Verified internet access from private EC2 via NAT

## 🛠️ Tools Used
AWS VPC, EC2, NAT Gateway, IGW, Security Groups
