🚀 Deploy a Static Web App with Docker, Amazon ECR, and Amazon ECS
This project demonstrates how to deploy a scalable static website using Docker, Amazon ECR, and Amazon ECS. Follow the sequence below to set up your infrastructure and deploy your web app in a dynamic and secure environment.

🗂 Project Overview
This repository contains the necessary files and instructions to create a scalable web architecture. Below is a step-by-step guide covering all the tools, configurations, and services you’ll need for deployment.

🛠 Prerequisites
Create a Keypair

Enables SSH connection to GitHub.
Install Git

Provides version control and lets you clone the repository locally.
Install VS Code

Use as your code editor and terminal interface.
Sign up for Docker Hub

Hosts your Docker images online.
Download and Install Docker

Manage containers and build images locally.
📝 Deployment Steps
Step 1: Prepare the Code
Create a GitHub Repository

Store your Dockerfile and project code.
Clone the Repository to Your Local Machine

Access and edit the repository files on your computer.
Create a Dockerfile

Use the provided code in this repo to define your container.
Build and Start the Docker Container

Compile and run the image with your application.
Step 2: Configure AWS & Docker
Install AWS CLI

Run AWS commands locally via the command line.
Create an IAM User & Access Keys

Configure CLI access to AWS services.
Create an Amazon ECR Repository

Push your Docker image to ECR for storage.
Step 3: Network & Compute Setup
Build a Three-Tier VPC from Scratch

Organize resources across subnets for better availability.
Create NAT Gateways, Security Groups & ALB

Secure and route traffic across your network.
Create an ECS Cluster, Task Definition & Service

Set up ECS to run your container-based web app.
Step 4: Configure Domain & Security
Create a Domain Name & Record Set in Route 53
Assign a user-friendly address to your website.
Create SSL Certificates & HTTPS Listener
Enable secure access for users via HTTPS.
🛡 Security & Monitoring
Use IAM roles and policies to secure AWS access.
Monitor your infrastructure using CloudWatch for logs and metrics.
🎯 Outcome
By the end of this guide, you will have a fully functional, scalable, and secure static web app deployed on Amazon ECS using Docker containers and ECR for image storage.

📢 Feedback
If you encounter issues or have feedback, please open an issue in this repository.

📄 License
This project is licensed under the MIT License – see the LICENSE file for details.

📧 Contact
For any inquiries, reach out to the repository maintainer.
