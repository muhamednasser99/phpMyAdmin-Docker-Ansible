# Ansible + Docker Automation Project

## 📖 Overview
This project demonstrates how to automate the setup of Docker and deploy containers using **Ansible**.  
The goal is to configure a remote target machine, install Docker, and deploy a MySQL database with a phpMyAdmin frontend, all through automation.

---

## ⚙️ Steps

### 1️⃣ Ansible Setup
- Prepare **SSH access** to the target machine.
- Define the **Ansible inventory/target**.
- Create **Ansible playbooks** to initialize the target.

### 2️⃣ Docker Automation with Ansible
- Install Docker on the target machine.
- Create a **custom Docker network**.
- Create **persistent volumes**.
- Deploy 2 containers:
  - **MySQL (db)**
  - **phpMyAdmin (frontend)**

---

## 🚀 Tools & Technologies
- **Ansible** – IT automation & configuration management.  
- **Docker** – containerization platform.  
- **MySQL** – database.  
- **phpMyAdmin** – web-based DB management tool.  

---

## 📌 Future Improvements
- Add Docker Compose integration.    
- Role-based Ansible structure.  

---

## 📷 Project Workflow
1. Configure SSH & inventory.  
2. Run the Ansible playbook.  
3. Docker is installed & containers deployed.  
4. Access MySQL via phpMyAdmin frontend.  
