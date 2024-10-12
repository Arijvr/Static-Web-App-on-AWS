# 🚀 Deploy a Static Web App with Docker, Amazon ECR, and Amazon ECS  

This project demonstrates how to deploy a scalable static website using **Docker**, **Amazon ECR**, and **Amazon ECS**. Follow the sequence below to set up your infrastructure and deploy your web app in a dynamic and secure environment.

---

## 🗂 Project Overview  

This repository contains the necessary files and instructions to create a scalable web architecture. Below is a step-by-step guide covering all the tools, configurations, and services you’ll need for deployment.

---

## 🛠 Prerequisites  

1. **Create a Keypair**  
   - Enables SSH connection to GitHub.

2. **Install Git**  
   - Provides version control and lets you clone the repository locally.

3. **Install VS Code**  
   - Use as your code editor and terminal interface.

4. **Sign up for Docker Hub**  
   - Hosts your Docker images online.

5. **Download and Install Docker**  
   - Manage containers and build images locally.

---

## 📝 Deployment Steps  

### Step 1: Prepare the Code  
1. **Create a GitHub Repository**  
   - Store your Dockerfile and project code.

2. **Clone the Repository to Your Local Machine**  
   - Access and edit the repository files on your computer.

3. **Create a Dockerfile**  
   - Use the provided code in this repo to define your container.

4. **Build and Start the Docker Container**  
   - Compile and run the image with your application.

---

### Step 2: Configure AWS & Docker  
5. **Install AWS CLI**  
   - Run AWS commands locally via the command line.

6. **Create an IAM User & Access Keys**  
   - Configure CLI access to AWS services.

7. **Create an Amazon ECR Repository**  
   - Push your Docker image to ECR for storage.

---

### Step 3: Network & Compute Setup  
8. **Build a Three-Tier VPC from Scratch**  
   - Organize resources across subnets for better availability.

9. **Create NAT Gateways, Security Groups & ALB**  
   - Secure and route traffic across your network.

10. **Create an ECS Cluster, Task Definition & Service**  
   - Set up ECS to run your container-based web app.

---

### Step 4: Configure Domain & Security  
11. **Create a Domain Name & Record Set in Route 53**  
   - Assign a user-friendly address to your website.

12. **Create SSL Certificates & HTTPS Listener**  
   - Enable secure access for users via HTTPS.

---

## 🛡 Security & Monitoring  
- Use **IAM roles and policies** to secure AWS access.  
- Monitor your infrastructure using **CloudWatch** for logs and metrics.

---

## 🎯 Outcome  
By the end of this guide, you will have a fully functional, scalable, and secure static web app deployed on Amazon ECS using Docker containers and ECR for image storage.

---

## 📢 Feedback  
If you encounter issues or have feedback, please open an issue in this repository.

---

### 📄 License  
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

## 📧 Contact  
For any inquiries, reach out to the repository maintainer.
