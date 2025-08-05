# 🔓 Host Header Injection – Vulnerable Password Reset Web App

This project is a deliberately vulnerable web application created for the purpose of demonstrating **Host Header Injection** in password reset flows. It allows you to simulate how an attacker can exploit the `Host` HTTP header to hijack accounts if the reset link is generated insecurely.

## 📚 What You'll Learn

- How password reset links are typically generated
- How insecure handling of `Host` headers can lead to account takeover
- How to simulate the attack using Postman or Burp Suite
- Best practices to secure the password reset process

## 🛠 Tech Stack

- Node.js + Express.js
- HTML/CSS (basic frontend)
- UUID (for reset token generation)

## 🚀 Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/Bbrnn/host-header-reset-demo.git
cd host-header-reset-demo
