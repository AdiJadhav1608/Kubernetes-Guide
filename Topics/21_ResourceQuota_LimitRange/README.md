━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 🚧 ResourceQuota & LimitRange
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

ResourceQuota and LimitRange help **control and govern resource usage** within a namespace.

They prevent resource abuse and ensure fair allocation.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧠 What is ResourceQuota?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

ResourceQuota limits the total amount of resources used in a namespace.

It applies to CPU, memory, Pods, Services, and more.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧠 What is LimitRange?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

LimitRange sets default and maximum/minimum limits for containers.

It enforces resource constraints at the container or Pod level.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🔁 How They Work Together
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

LimitRange controls individual container usage.

ResourceQuota controls total namespace usage.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 📌 Common Use Cases
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Multi-tenant clusters  
- Cost control  
- Preventing noisy neighbors  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🌟 Best Practices
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Always define quotas in shared namespaces  
- Combine with RBAC for security  
- Monitor quota usage  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧭 What You Will Learn Next
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Next, you will learn about Autoscaling concepts.

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
