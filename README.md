### LITA-CLOUD-COMPUTING-FINAL-PROJECT
 A project showing the provisioning of EC2 instance in AWS environment
 ### AWS Web Application
 ## OVERVIEW
 This project is a scalable and secure web application hosted on AWS. 
 It utilizes various AWS services to ensure high availability, effective scalability and optimal perfomrance as well as efficient reliability.
  The setup is designed to provide seamless deployment and structured resource management.
## ARCHITECTURE
The ARCHITECTURE includes the following AWS services:
# IAM:
Roles and polices created for secure and restricted access to the AWS resources.
# Virtual Private Cloud (VPC)
Provides a secure and Isolated network environment for the application
Configured with Public and private subnets for better security.
Includes a NAT Gateway to allow outbound internet access for private subnets.
## Configuration Details
# VPC Configuration
VPC CIDR block: 10.0.0.0/16
# Subnets:
Public Subnet: 10.0.0.0/20
Private Subnet: 10.0.128.0/24
# Internet Gateway
Attached to the public subnet.
# NAT Gateway:
Configured to provide internet access to resources in private subnets
### EC2 Configuration 
# AMI:
 Amazon Linux 2

# Instance Type: 
t2.micro

# Key Pair:
 My-keypair.pem

# Security Group:
Inbound rules:
 Restrict SSH (port 22) access to your IP addresses only


Outbound rules: 
Allow HTTP(port 80) and HTTPS(port 443) traffic from the internet.


# SCREENSHOTS
 # VPC DASHBOARD
![vpc1](https://github.com/user-attachments/assets/98921d45-6e6c-4100-a7e5-447afc4e43be)



# EC2 DASHBOARD
![EC2](https://github.com/user-attachments/assets/c0115579-4408-4978-99d1-12396bd99728)



