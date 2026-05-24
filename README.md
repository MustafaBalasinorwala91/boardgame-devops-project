# Automating Secure Deployment of BoardGame Listing WebApp on AWS

## 📌 Project Overview

This project demonstrates an end-to-end DevOps implementation for securely deploying a BoardGame Listing Web Application on AWS using modern DevOps tools and practices.

The project focuses on:

- Infrastructure Automation
- CI/CD Pipeline Implementation
- Security Scanning
- Monitoring & Logging
- Database Management
- Scalability & High Availability

The complete workflow automates infrastructure provisioning, application deployment, monitoring, and scalable architecture setup.

---

# 🚀 Tech Stack

| Tool / Service | Purpose |
|---|---|
| Terraform | Infrastructure as Code |
| Ansible | Configuration Management |
| GitHub Actions | CI/CD Automation |
| Maven | Java Build Tool |
| Docker | Containerization |
| AWS EC2 | Cloud Hosting |
| Trivy | Vulnerability Scanning |
| Grafana | Monitoring Dashboard |
| H2 Database | Database Management |
| Spring Boot | Java Web Application |

---

# 🏗️ Project Architecture

```text
Developer
   ↓
GitHub Repository
   ↓
GitHub Actions CI/CD
   ↓
Maven Build
   ↓
Docker Image Build
   ↓
Trivy Security Scan
   ↓
AWS EC2 Deployment
   ↓
Grafana Monitoring
   ↓
Persistent H2 Database
   ↓
Scalable Infrastructure using Terraform
