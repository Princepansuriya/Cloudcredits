Windows Virtual Machine Deployment on AWS

This project demonstrates how to deploy and configure a Windows Server Virtual Machine (EC2 instance) on Amazon Web Services (AWS). It provides a step-by-step guide for beginners and professionals to quickly spin up a Windows environment in the cloud.

Steps Covered : 
1. Login to AWS Console – Access the AWS Management Console.
2. Launch EC2 Instance – Select Windows Server AMI (2019/2022).
3. Choose Instance Type – Start with t2.micro (Free Tier) or scale up.
4. Key Pair Setup – Generate or use an existing key pair for secure login.
5. Configure Networking –
6. Attach instance to a VPC and Subnet
7. Assign Public IP
8. Configure Security Group to allow RDP (3389)
9. Add Storage – Minimum 30 GB SSD (expandable).
10. Launch Instance – Boot up the VM.
11. Connect to VM –
12. Decrypt admin password using .pem file
13. Download .rdp file and log in via Remote Desktop
14. Elastic IP (Optional) – Assign a static IP for persistent access.
15. Manage Costs – Stop or terminate instance when not in use

<img width="1842" height="959" alt="image" src="https://github.com/user-attachments/assets/19b21ced-456d-458c-b5f7-0c904916f572" />
