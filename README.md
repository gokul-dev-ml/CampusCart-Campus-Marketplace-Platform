# CampusCart – Campus Marketplace Platform

## Project Overview

CampusCart is a cloud-hosted campus marketplace web application designed to help students buy and sell products within their college community through a simple and user-friendly platform. The application provides categorized product listings, search functionality, and a responsive user interface optimized for both desktop and mobile devices.

The project was successfully deployed on an AWS EC2 Ubuntu instance using Nginx as the production web server. This project provided practical experience in frontend development, cloud deployment, Linux server management, and production hosting workflows.


---

# Project Screenshots

## Home Page

<img width="787" height="574" alt="Screenshot From 2026-05-24 08-56-44" src="https://github.com/user-attachments/assets/4ee7e454-bab2-447e-ae0a-3aad53d741a6" />


## Product Browse Page

<img width="787" height="574" alt="Screenshot From 2026-05-24 08-57-13" src="https://github.com/user-attachments/assets/81f0c494-03ca-4f32-bfe5-23c80b983250" />


---

# Technologies Used

## Frontend Development

* React.js
* Vite
* JavaScript
* HTML5
* CSS3

## Cloud & Deployment

* AWS EC2
* Ubuntu Linux
* Nginx Web Server
* SSH
* SCP
* Linux Command Line

## Tools & Utilities

* Git & GitHub
* VS Code
* Terminal / Bash

---

# Project Features

## Product Marketplace

* Students can browse listed products
* Product categories for easy navigation
* Product cards with pricing and details
* Recently added products section

## Search Functionality

* Search products dynamically
* Category-based filtering
* Product sorting options

## Responsive User Interface

* Mobile-friendly layout
* Modern UI design
* Interactive navigation
* Clean user experience

## Cloud Deployment

* Hosted on AWS EC2
* Configured Nginx for production hosting
* Deployed optimized production build files

---

# Application Workflow

1. Frontend developed using React.js and Vite
2. Production build generated using Vite build process
3. AWS EC2 Ubuntu instance launched
4. SSH authentication configured using PEM key
5. Nginx installed and configured
6. Build files transferred securely using SCP
7. Website hosted through Nginx on EC2

---

# AWS Deployment Architecture

| Component   | Purpose                       |
| ----------- | ----------------------------- |
| AWS EC2     | Cloud virtual server hosting  |
| Ubuntu      | Linux server operating system |
| Nginx       | Production web server         |
| SSH         | Secure remote server access   |
| SCP         | Secure file transfer          |
| React Build | Frontend production files     |

---

# Deployment Steps Performed

## 1. EC2 Instance Setup

* Created Ubuntu EC2 instance on AWS
* Configured Security Groups
* Enabled HTTP and SSH access

## 2. Server Configuration

* Connected to EC2 using SSH and PEM key
* Updated Ubuntu packages
* Installed Nginx web server

## 3. Frontend Build Process

* Built optimized React production files using:

```bash
npm run build
```

## 4. Secure File Transfer

Transferred build files to EC2 server using SCP:

```bash
scp -i key.pem -r dist/* ubuntu@<public-ip>:/var/www/html/
```

## 5. Nginx Configuration

* Configured Nginx root directory
* Restarted Nginx service
* Verified website accessibility

---

# Linux & Cloud Concepts Learned

## AWS EC2

Learned how to provision and manage cloud virtual servers using AWS.

## Ubuntu Linux Administration

Worked with Linux commands, package management, file permissions, and server configuration.

## Nginx Web Hosting

Configured Nginx as a reverse proxy and static web server.

## SSH Authentication

Used PEM keys for secure remote server access.

## SCP File Transfer

Learned secure deployment workflows using SCP.

## Production Deployment

Understood how frontend applications are deployed in real cloud environments.

---

# Key Learning Outcomes

* Developed and deployed a production-ready React application
* Gained practical experience with AWS cloud infrastructure
* Learned Linux server management fundamentals
* Understood web server configuration using Nginx
* Practiced secure SSH-based remote access
* Improved troubleshooting and deployment skills
* Learned cloud hosting workflows for frontend applications
* Strengthened DevOps and cloud engineering fundamentals

---

# Security Practices Followed

* Used SSH key-based authentication
* Restricted server access through Security Groups
* Configured only required inbound ports
* Avoided exposing sensitive credentials publicly

---

# Future Enhancements

* Backend API integration
* Database integration using MySQL or MongoDB
* User authentication system
* Payment gateway integration
* Docker container deployment
* CI/CD automation pipeline
* HTTPS configuration with SSL certificates
* Domain configuration using Route 53

---

# Real-World Relevance

This project simulates real-world frontend deployment workflows commonly used in production environments. The technologies and deployment practices used in this project are widely adopted in cloud engineering, DevOps, and full-stack development roles.

The project helped build practical skills in:

* Cloud Hosting
* Linux Administration
* Web Server Configuration
* Secure Deployment
* Frontend Production Deployment
* AWS Infrastructure Management

---

# Author

## Gokul M

Aspiring Cloud Engineer | AWS | Linux | Networking | DevOps Learner

### LinkedIn

https://www.linkedin.com/in/gokul-m05/

### GitHub

https://github.com/gokul-dev-ml

---

# Tags

AWS
Amazon EC2
Cloud Computing
React.js
Vite
Nginx
Ubuntu
Linux
Web Hosting
Cloud Engineering
Frontend Deployment
DevOps
SSH
SCP
Cloud Infrastructure
AWS Cloud
Production Deployment
Static Hosting
Linux Administration
