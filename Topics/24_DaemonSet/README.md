━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 🧭 Kubernetes DaemonSet
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

DaemonSets ensure that **a specific Pod runs on every node** in the cluster.

They are commonly used for cluster-wide services.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧠 What is a DaemonSet?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

A DaemonSet runs one copy of a Pod on each node.

When new nodes are added, Pods are automatically scheduled.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🎯 Common Use Cases
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Log collection agents  
- Monitoring agents  
- Network plugins  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## ⚙️ How DaemonSets Work
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

DaemonSet controller ensures Pod placement.

Pods are removed automatically when nodes are removed.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🌟 Best Practices
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Use node selectors if required  
- Avoid heavy workloads  
- Monitor resource usage  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧭 What You Will Learn Next
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Next, you will learn about StatefulSets.

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
