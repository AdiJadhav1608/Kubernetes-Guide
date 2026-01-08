━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 🔐 Kubernetes Secrets
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Secrets are used to store **sensitive information** such as passwords, tokens, and keys.

They help keep confidential data separate from application code.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧠 What is a Secret?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

A Secret is a Kubernetes object that stores sensitive data securely.

The data is encoded (Base64) and can be injected into Pods safely.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🎯 Why Use Secrets?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Secrets prevent hardcoding credentials in YAML files.

They improve security and follow best practices for configuration management.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🔑 What Can Be Stored?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Database usernames & passwords  
- API keys & tokens  
- TLS certificates  
- SSH keys  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🔁 How Secrets Are Used
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- As environment variables  
- As mounted files inside Pods  
- By applications at runtime  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## ⚠️ Important Notes
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Secrets are Base64 encoded, not encrypted by default.

Use RBAC and encryption at rest for better security.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🌟 Best Practices
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Never commit real secrets to GitHub  
- Use encryption at rest  
- Rotate secrets regularly  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧭 What You Will Learn Next
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Next, you will learn about Volumes and Persistent Storage.

---

# 🤝 Contribute
Add more commands, diagrams, or revision notes to help learners revise Docker faster.

---

# 👨‍💻 Author
**Aditya Jadhav**  
Beginner Cloud & DevOps Learner  

📧 **adijadhav8446@gmail.com**  
🌐 **GitHub Profile:** https://github.com/AdiJadhav1608  
🔗 **LinkedIn:** https://www.linkedin.com/in/aditya-jadhav-718087339/  

⭐ *If you found this helpful, give it a star and keep learning Kubernetes !*
