# Linux Server Setup on GCP

## 📌 Project Objective
To deploy and configure a Linux server on Google Cloud Platform (GCP) and host a static website using Nginx.

---

## 🛠️ Technologies Used
- Google Cloud Platform (Compute Engine)
- Ubuntu Linux
- Nginx
- SSH
- Firewall Configuration

---

## 🏗️ Architecture Overview

User → Public IP → GCP VM (Ubuntu) → Nginx → Static Website

---

## 🚀 Implementation Steps

1. Created GCP e2-micro VM (Free Tier - US region)
2. Connected via SSH
3. Installed Nginx
4. Configured firewall rules for HTTP (port 80)
5. Hosted static HTML page

---

## 🔒 Security Configurations
- Used SSH key-based login
- Configured firewall rules properly

---

## 📷 Screenshots
![Website Screenshot](screenshots/website.png)

![VM Screenshot](screenshots/vm.png)


---

## 🌐 Deployment Summary

The web server was successfully deployed on a GCP Compute Engine VM.
The application was tested via public IP and verified in a browser.

*(Instance terminated after testing to prevent unnecessary billing.)*

## 🎯 Learning Outcomes
- Understanding Linux server setup
- Basic networking (IP, ports)
- Firewall rule configuration
- Hosting web application on cloud VM
