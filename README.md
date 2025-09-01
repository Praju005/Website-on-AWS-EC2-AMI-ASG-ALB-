# AWS EC2 Auto Scaling Website with ALB

This project demonstrates deploying a **static website** on AWS using **EC2**, **AMI**, **Auto Scaling**, and **Application Load Balancer (ALB)**.  
The setup ensures **high availability** and **scalability** for variable traffic loads.

---

## 🚀 Features
- **EC2 Instance**: Hosts the static website files.
- **AMI (Amazon Machine Image)**: Custom image with website code for quick instance launches.
- **Auto Scaling Group (ASG)**: Automatically scales instances based on traffic demand.
- **Application Load Balancer (ALB)**: Distributes traffic evenly across instances.
- **DNS Integration**: Maps domain name to the Load Balancer for user-friendly access.

---

## 🛠️ Tech Stack
- **AWS EC2** for hosting
- **AWS AMI** for reusable instance images
- **AWS Auto Scaling Group** for scaling
- **AWS ALB** for load balancing
- **HTML/CSS/JS** for frontend website

---

## 📂 Project Structure
/project-root
    ├── index.html       # Main website file
    ├── user-data.sh     # Script for setting up the website
    └── README.md        # Project documentation

---

## ⚙️ Setup Steps
1. Launch EC2 instance and upload your static website files.
2. Create AMI from the instance.
3. Create Launch Template using the AMI.
4. Set up Auto Scaling Group with the Launch Template.
5. Configure Application Load Balancer and attach ASG.
6. Access website using ALB DNS or custom domain.

---

## 🎯 Learning Outcomes
- Deploying static websites on AWS EC2
- Creating reusable AMIs
- Setting up Auto Scaling Groups
- Configuring Application Load Balancer
- Understanding scalable web architecture

---

## 🌐 Access
Once deployed, your website can be accessed via:
http://<ALB-DNS-Name>

---
