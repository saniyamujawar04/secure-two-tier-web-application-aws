# Secure Two-Tier Web Application on AWS

## Project Overview

This project demonstrates the deployment of a secure Two-Tier Web Application using Amazon Web Services (AWS). The architecture consists of a web application layer hosted on Amazon EC2 and a database layer hosted on Amazon RDS.

The application provides a user registration interface developed using HTML, CSS, and JavaScript. User information is stored in Amazon RDS (MySQL), while uploaded files are stored in Amazon S3. AWS IAM, VPC, Security Groups, and AWS Secrets Manager are used to implement secure access control, networking, and credential management.

---

## Architecture Diagram

![AWS Architecture](AWS%202-Tier%20Web%20Application%20Architecture.png)

---

## AWS Services Used

* Amazon EC2
* Amazon RDS (MySQL)
* Amazon S3
* AWS IAM
* AWS Secrets Manager
* Amazon VPC
* Security Groups

---

## Technologies Used

* AWS Cloud
* HTML
* CSS
* JavaScript
* MySQL
* Linux (Ubuntu)

---

## Key Features

* User Registration System
* Secure File Upload to Amazon S3
* User Data Storage in Amazon RDS
* IAM-Based Access Control
* Secure Credential Management
* Virtual Private Cloud (VPC) Configuration
* Security Group Configuration
* Database Connectivity
* Cloud-Based Deployment
* Two-Tier Architecture Implementation

---

## Project Structure

```text
loginpage-main/
│
├── .github/
├── .gitignore
├── index.html
├── style.css
├── package.json
└── package-lock.json
```

---

## Project Workflow

1. User accesses the web application hosted on Amazon EC2.
2. User enters registration details through the web interface.
3. Application processes and stores user information in Amazon RDS.
4. Uploaded files are securely stored in Amazon S3.
5. IAM roles and Security Groups control access between AWS resources.
6. AWS Secrets Manager securely stores sensitive credentials.
7. The application returns a successful response to the user.

---

## Architecture Components

### Application Layer

* Hosted on Amazon EC2
* Frontend developed using HTML, CSS, and JavaScript
* Handles user interactions and data submission

### Database Layer

* Hosted on Amazon RDS (MySQL)
* Stores user registration information

### Storage Layer

* Amazon S3 Bucket
* Stores uploaded user files securely

### Security Layer

* AWS IAM Roles and Policies
* Security Groups
* AWS Secrets Manager
* VPC Network Isolation

---

## Skills Demonstrated

* AWS Cloud Computing
* Linux Administration
* VPC Configuration
* IAM Roles and Policies
* Security Group Management
* Database Connectivity
* Cloud Security
* Web Application Deployment
* Amazon S3 Storage Management
* Networking Fundamentals
* AWS Infrastructure Deployment

---

## Security Implementation

* Configured VPC with secure networking.
* Implemented Security Groups to control inbound and outbound traffic.
* Used IAM roles and policies for resource access management.
* Stored sensitive credentials securely using AWS Secrets Manager.
* Restricted database access to authorized resources only.

---

## Testing Performed

### Functional Testing

* User Registration
* File Upload
* Database Storage

### Integration Testing

* EC2 to RDS Connectivity
* EC2 to S3 Integration
* AWS Service Connectivity

### Security Testing

* IAM Permission Validation
* Security Group Verification
* Credential Protection

---

## Challenges Faced

* Configuring secure connectivity between Amazon EC2 and Amazon RDS.
* Managing IAM roles and permissions.
* Configuring Security Groups and VPC networking.
* Integrating Amazon S3 for file storage.
* Troubleshooting cloud deployment and connectivity issues.

---

## Project Outcome

Successfully deployed a secure cloud-based Two-Tier Web Application demonstrating AWS infrastructure management, networking, security implementation, database integration, file storage, and cloud deployment best practices.

---

## Future Enhancements

* Application Load Balancer (ALB)
* Auto Scaling Group (ASG)
* AWS CloudWatch Monitoring
* CI/CD Pipeline using Jenkins
* Docker Containerization
* Kubernetes Deployment
* Multi-Tier Architecture

---

## Author

**Saniya Faruque Mujawar**

Aspiring DevOps Engineer | AWS Cloud | Linux | Jenkins | Docker | GitHub | CI/CD
