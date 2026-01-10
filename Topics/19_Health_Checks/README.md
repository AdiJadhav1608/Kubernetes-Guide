━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# ❤️ Kubernetes Health Checks
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Health checks help Kubernetes determine **whether a container is running correctly**.

They ensure application reliability and automatic recovery.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧠 What are Health Checks?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Health checks are probes used by Kubernetes.

They continuously monitor the state of containers.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🔍 Types of Health Checks
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Liveness Probe  
- Readiness Probe  
- Startup Probe  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## ❤️ Liveness Probe
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Checks if the container is still alive.

If it fails, Kubernetes restarts the container.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🚦 Readiness Probe
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Checks if the container is ready to receive traffic.

If it fails, traffic is stopped but the container is not restarted.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🚀 Startup Probe
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Checks if the application has started successfully.

Useful for slow-starting applications.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🌟 Best Practices
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Always define readiness probes  
- Use startup probes for heavy applications  
- Avoid aggressive probe intervals  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧭 What You Will Learn Next
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Next, you will learn about Resource Requests and Limits.

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
