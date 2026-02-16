# VPC Peering & Private EC2 Communication

## 📌 Objective
Enable secure communication between two isolated VPCs without exposing instances to the internet.

## 🏗️ Architecture
- Two VPCs with non-overlapping CIDR blocks
- VPC Peering connection
- Updated route tables for cross-VPC traffic
- EC2 in each VPC

## 🔐 Security Implementation
- No public IPs on private EC2
- SSH allowed only from specific CIDR
- Controlled inbound traffic using Security Groups

## ✅ Validation
- Successfully SSH from EC2 in VPC-A to EC2 in VPC-B
- Verified routing configuration

## 🛠️ Tools Used
AWS VPC, EC2, VPC Peering, Route Tables, Security Groups
