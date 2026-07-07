# 🌐 Uday's Portfolio

A personal portfolio website of **Gella Uday Kumar** showcasing my journey as a **DevOps Engineer**, Cloud Enthusiast, and Automation Learner.

This project is more than just a portfolio website—it's deployed using real-world DevOps practices on AWS with a custom domain, Nginx, and HTTPS.

---

## 🚀 Live Website

**Portfolio:** https://udaydev.site

---

## 📸 Preview

Below is a preview of the portfolio homepage hosted on AWS EC2 using Nginx with a custom domain and HTTPS.

![Portfolio Preview](assets/preview.png)

---

# ✨ Features

- Responsive modern portfolio
- Dark theme UI
- Mobile-friendly design
- Animated gradients
- Smooth scrolling navigation
- Download Resume
- Certifications section
- Projects section
- Contact information
- GitHub & LinkedIn integration
- HTTPS secured website
- Custom domain

---

# 🛠 Tech Stack

### Frontend

- HTML5
- CSS3
- JavaScript

### DevOps & Cloud

- AWS EC2 (Ubuntu)
- Nginx
- GoDaddy DNS
- Let's Encrypt SSL
- Git
- GitHub
- SSH

---

# ☁️ Deployment Architecture

```
User Browser
      │
      ▼
https://udaydev.site
      │
      ▼
GoDaddy DNS
      │
      ▼
AWS EC2 (Ubuntu)
      │
      ▼
Nginx Web Server
      │
      ▼
Portfolio Website
```

---

# 📂 Project Structure

```
portfolio/
│
├── assets/
│   ├── profile.png
│   ├── preview.png
│   └── Gella_Uday_Kumar_Resume.pdf
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

# 🚀 Deployment Steps

### 1. Clone Repository

```bash
git clone https://github.com/Gella-Uday-kumar/portfolio.git
```

---

### 2. Copy Portfolio to EC2

```bash
scp -r portfolio ubuntu@<EC2-Public-IP>:/var/www/html
```

---

### 3. Configure Nginx

- Install Nginx
- Configure Server Block
- Point document root to `/var/www/html`

---

### 4. Configure Domain

Purchased domain from GoDaddy

Configured:

- A Record → EC2 Public IP
- CNAME → www

---

### 5. Enable HTTPS

Installed

- Certbot
- Let's Encrypt SSL

Generated SSL certificate for

- udaydev.site
- www.udaydev.site

Configured automatic renewal.

---

# 📚 Skills Demonstrated

- Linux Administration
- AWS EC2
- Nginx
- Domain Configuration
- DNS Management
- HTTPS Configuration
- SSL Certificates
- Git & GitHub
- SSH
- Web Hosting

---

# 📈 Future Improvements

- Docker Containerization
- Jenkins CI/CD
- GitHub Actions
- Terraform
- Kubernetes Deployment
- Prometheus Monitoring
- Grafana Dashboard

---

# 👨‍💻 About Me

**Gella Uday Kumar**

DevOps Engineer | Cloud Enthusiast | AWS Learner

📍 Bengaluru, India

📧 gellaudaykumar2329@gmail.com

---

## 🌐 Connect With Me

- Portfolio: https://udaydev.site
- GitHub: https://github.com/Gella-Uday-kumar
- LinkedIn: https://www.linkedin.com/in/gella-uday-kumar/

---

# ⭐ If you like this project

Please consider giving it a ⭐ on GitHub.
