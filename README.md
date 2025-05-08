📦 Serverless 3-Tier Web Application on AWS

This repository contains a fully serverless 3-tier web application architecture built on AWS, designed for scalability, security, and cost-efficiency.

📺 Architecture Overview Video

For a detailed explanation of the architecture, I made a video of me explainig it in details you will find the link below 
if the video is too slow for you .... well 😅😅 

video link : 

🧱 Architecture Diagram
I am still making some changes on the diagram 


🧩 Project Overview

This project demonstrates a modern serverless 3-tier architecture on AWS, comprising:

* **Presentation Layer**: An Application Load Balancer (ALB) that routes incoming traffic to the application.
* **Application Layer**: A containerized web application deployed on Amazon ECS Fargate within a private subnet.
* **Data Layer**: An Amazon RDS MySQL database instance residing in a private DB subnet.

Additional AWS services utilized include:

* **AWS Secrets Manager**: For secure storage and management of database credentials.
* **AWS Lambda**: To automate the rotation of secrets in Secrets Manager.
* **AWS CloudFormation**: For infrastructure as code (IaC) to provision and manage resources.

## 💡 Business Problem Solved

Traditional web applications often face challenges in scalability, security, and cost management. This serverless architecture addresses these issues by:

* **Scalability**: Leveraging ECS Fargate to automatically scale the application based on demand.
* **Security**: Implementing VPC isolation, private subnets, and secure secret management.
* **Cost-Efficiency**: Eliminating the need for server management and optimizing resource utilization.


