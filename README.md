# 🚀 Terraform AWS - Infrastructure as Code (CCP DevOps)

Ce projet démontre la mise en place d’une infrastructure cloud automatisée sur AWS en utilisant **Terraform (Infrastructure as Code)**.

---

## 📌 Objectif

Automatiser le déploiement d’une infrastructure cloud comprenant :

- Une instance EC2 (Ubuntu)
- Un Security Group (SSH + HTTP)
- Un serveur web Nginx installé automatiquement
- Une configuration entièrement reproductible

---

## 🏗️ Architecture

- AWS EC2 (t2.micro)
- AWS Security Group
- Ubuntu 24.04 LTS
- Nginx web server
- Terraform IaC

---

## ⚙️ Technologies utilisées

- AWS (EC2, Security Groups)
- Terraform
- Ubuntu Server
- Nginx
- Git / GitHub

---

## 🚀 Déploiement

### 1. Initialiser Terraform
```bash
terraform init
