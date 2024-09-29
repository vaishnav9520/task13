# Free Virtual Machine Deployment on AWS

## Overview
This task involved launching a free Virtual Machine (VM) on AWS, configuring it, verifying connectivity, and accessing it via SSH. The process utilized AWS EC2 to demonstrate cloud VM management.

## EC2 Instance Launch Process

1. Accessed the EC2 Console: Logged into the AWS Management Console and navigated to the EC2 Dashboard.
2. Started EC2 Instance Launch: Clicked the Launch Instance button to initiate the instance creation process.
3. Selected the Amazon Machine Image (AMI): Chose the Amazon Linux AMI, which is free-tier eligible.
4. Chose Instance Type: Selected t2.micro instance type for light workloads and created a key pair named cloudkey.
5. Configured Instance Details: Used the default VPC and standard options for networking.
6. Set Up Security Group Rules: Configured rules to allow SSH (port 22) access and enabled ICMP for ping tests.
7. Final Review and Launch: Reviewed settings and launched the EC2 instance successfully.

## Connectivity Testing and Instance Access

- Verified the public IP connectivity by pinging the assigned public IP 35.171.158.25 after adjusting security group rules.
- Accessed the EC2 instance via SSH using the cloudkey
- Attempted to ping the public IP from within the EC2 instance but faced ISP restrictions.

## Termination of the VM
The VM was properly shut down and terminated to prevent any charges.

## Summary of Results
1. Successfully launched a free-tier VM on AWS and obtained its public IP.
2. Enabled connectivity to the VM through security group adjustments.
3. Accessed the VM via SSH and verified configurations.
4. Terminated the VM after task completion to avoid unnecessary costs.
