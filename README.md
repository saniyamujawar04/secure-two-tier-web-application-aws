# Secure Two-Tier Web Application on AWS

## Project Overview

This project demonstrates the design and deployment of a secure Two-Tier Web Application using Amazon Web Services (AWS). The architecture consists of a web application layer hosted on Amazon EC2 and a database layer hosted on Amazon RDS.

The application allows users to register and upload files through a web interface. User information is securely stored in Amazon RDS, while uploaded files are stored in Amazon S3. AWS IAM, Security Groups, VPC, and AWS Secrets Manager are used to implement secure access control, networking, and credential management.

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
* Node.js
* Express.js
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
* Secure Credential Management using AWS Secrets Manager
* Virtual Private Cloud (VPC) Configuration
* Security Group Configuration
* Database Connectivity from EC2
* Dynamic Data Retrieval
* Cloud-Based Deployment
* Error Handling and Input Validation
* Two-Tier Architecture Implementation

---

## Project Workflow

1. User accesses the web application hosted on Amazon EC2.
2. User submits registration details and uploads files.
3. Application validates user input and permissions.
4. Database credentials are securely retrieved from AWS Secrets Manager.
5. User data is stored in Amazon RDS.
6. Uploaded files are stored in Amazon S3.
7. IAM roles and Security Groups control access between AWS resources.
8. The application returns a secure response to the user.

---

## Architecture Components

### Application Layer

* Hosted on Amazon EC2
* Built using Node.js and Express.js
* Handles request processing and business logic

### Database Layer

* Hosted on Amazon RDS (MySQL)
* Stores user registration data and metadata

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
* File Storage Management
* Networking Fundamentals
* Secrets Management
* AWS Infrastructure Deployment

---

## Security Implementation

* Configured VPC with public and private networking.
* Implemented Security Groups to restrict unauthorized access.
* Used IAM roles and policies for resource-level permissions.
* Stored sensitive credentials securely using AWS Secrets Manager.
* Restricted database access to trusted resources only.
* Implemented secure communication between application and database layers.

---

## Testing Performed

### Functional Testing

* User Registration
* File Upload
* Database Storage

### Integration Testing

* EC2 ↔ RDS Connectivity
* EC2 ↔ S3 Integration
* Secrets Manager Integration

### Security Testing

* IAM Permission Validation
* Security Group Verification
* Credential Protection

### Validation Testing

* Input Validation
* Error Handling

---

## Challenges Faced

* Configuring secure connectivity between Amazon EC2 and Amazon RDS.
* Managing IAM roles and permissions.
* Integrating AWS Secrets Manager with the application.
* Configuring Security Groups and network access controls.
* Implementing secure file upload and storage in Amazon S3.
* Troubleshooting deployment and connectivity issues.

---

## Project Outcome

Successfully deployed a secure cloud-based two-tier web application demonstrating AWS infrastructure management, networking, security implementation, database integration, file storage, and cloud deployment best practices.

---

## Future Enhancements

* Load Balancer Integration
* Auto Scaling Configuration
* AWS CloudWatch Monitoring
* CI/CD Pipeline Integration
* Multi-Tier Architecture
* Kubernetes Deployment
* Advanced Authentication Mechanisms

---

Author

Saniya Faruque Mujawar

Aspiring DevOps Engineer | AWS Cloud | Linux | CI/CD | Jenkins | Docker | GitHub

