# AWS EC2 Web Server Deployment

## Project Overview
This project documents my hands-on experience deploying web servers on AWS EC2 using both Linux and Windows Server instances. I practised configuring cloud instances, accessing remote servers, deploying a static website, and understanding how public IP addresses are used to access hosted applications.

## Objective
To understand how virtual machines work in AWS and gain practical experience deploying and accessing web applications through cloud infrastructure.

## Technologies & Services
- Amazon EC2
- Linux
- Windows Server
- Apache (HTTPD)
- Internet Information Services (IIS)
- SSH
- WinSCP
- Elastic IP
- AWS Management Console

## Implementation

### 1. EC2 Instance Creation
- Launched Linux and Windows Server instances using the AWS Management Console.
- Worked with instance configuration and storage settings.
- Used the Mumbai AWS Region for practice.

### 2. Remote Server Access
- Connected to Linux instances using SSH.
- Explored remote server access and file transfer using WinSCP.
- Practised managing files and working with server directories.

### 3. Web Server Deployment
- Installed and configured Apache (HTTPD) on a Linux instance.
- Used IIS on a Windows Server instance.
- Deployed a static Emoji Guessing Game created using HTML, CSS and JavaScript.

### 4. Public IP Address Management
- Explored the difference between public and private IP addresses.
- Practised allocating and associating an Elastic IP with an EC2 instance.
- Learned how a static public IP can provide a consistent endpoint for accessing a server.

## Key Learnings
- Understanding EC2 instance provisioning and cloud-based server management.
- Deploying web servers on Linux and Windows environments.
- Accessing remote instances using SSH.
- Transferring website files using WinSCP.
- Understanding public IP addresses and Elastic IP.
- Gaining practical exposure to cloud hosting and basic server troubleshooting.

## Project Evidence
Screenshots will be added to the `screenshots/` directory, including:
- EC2 instance configuration
- Linux Apache web server
- Windows IIS web server
- Deployed website
- Elastic IP configuration

## Repository Structure
```text
aws-ec2-web-server-deployment/
│
├── screenshots/
│   ├── ec2-instance.png
│   ├── apache-server.png
│   ├── iis-server.png
│   ├── deployed-website.png
│   └── elastic-ip.png
│
└── README.md
```

## Conclusion
This practical exercise helped me understand the fundamentals of cloud-based server deployment and strengthened my knowledge of AWS EC2, Linux administration, Windows Server, and web hosting.

## Cost and Security
- AWS resources should be stopped or terminated when no longer required.
- Never upload private SSH keys, passwords, or AWS credentials.
- Mask sensitive account information in screenshots.
