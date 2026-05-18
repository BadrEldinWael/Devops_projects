# 🚀 DevOps Projects Portfolio

This repository contains a collection of hands-on DevOps, Cloud, and Infrastructure projects focused on automation, CI/CD, Kubernetes, Terraform, AWS, and cloud-native technologies.

The projects are designed to demonstrate practical implementation of modern DevOps workflows and production-oriented infrastructure solutions.

---

# 📂 Projects Overview

## 🔹 Jenkins Shared Library

A reusable Jenkins Shared Library project that standardizes CI/CD pipeline workflows across multiple applications.

### Contents
- `vars/petclinicPipeline.groovy` — reusable Jenkins pipeline implementation
- Shared pipeline functions and automation logic

### Technologies Used
- Jenkins
- Groovy
- Docker
- CI/CD Pipelines

---

## 🔹 Kubernetes WordPress Deployment on AWS

Production-style Kubernetes deployment for hosting a WordPress application with a MySQL backend on AWS infrastructure.

### Contents
- `MySQL_yaml_files/`
  - MySQL Deployment
  - PVC
  - StorageClass
  - Secrets
  - Services

- `Wordpress_yaml_files/`
  - WordPress Deployment
  - PVC
  - StorageClass
  - Services

- `Kubeadm installtion scripts/`
  - Kubernetes master and worker node setup scripts

- `Images/`
  - Architecture diagrams and deployment screenshots

### Technologies Used
- Kubernetes
- AWS EC2
- EBS / EFS CSI Drivers
- Docker
- YAML Manifests
- Kubeadm

---

## 🔹 Terraform & CI/CD Pipeline on AWS

Infrastructure as Code (IaC) project for provisioning and managing AWS infrastructure using Terraform integrated with Jenkins CI/CD automation.

### Contents
- Terraform configuration files:
  - `main.tf`
  - `provider.tf`
  - `backend.tf`
  - `outputs.tf`
  - `variables.tf`
  - `terraform.tfvars`

- CI/CD:
  - `Jenkinsfile`

- Application:
  - `app/Dockerfile`
  - `app/index.html`

- Terraform Modules:
  - `modules/ec2`
  - `modules/iam`
  - `modules/monitoring`
  - `modules/rds`
  - `modules/vpc`

- `Screenshots/`
  - Infrastructure and pipeline execution screenshots

### Technologies Used
- Terraform
- Jenkins
- AWS
- Docker
- CI/CD Automation

---

# 🛠️ Technologies & Tools

| Category | Technologies |
|---|---|
| Cloud | AWS |
| Containers | Docker, Kubernetes, OpenShift |
| CI/CD | Jenkins |
| Infrastructure as Code | Terraform |
| Scripting | Bash |
| Version Control | Git & GitHub |

---

# 🎯 Repository Goals

- Build real-world DevOps projects
- Practice Infrastructure as Code (IaC)
- Implement CI/CD automation pipelines
- Deploy scalable cloud-native applications
- Improve Kubernetes and AWS administration skills

---

# 📌 Notes

- Each project is self-contained and may include its own documentation.
- Screenshots and YAML manifests are included where applicable.
- This repository is continuously updated with new DevOps and Cloud projects.

---

# 📫 Connect With Me

- GitHub: https://github.com/BadrEldinWael

---