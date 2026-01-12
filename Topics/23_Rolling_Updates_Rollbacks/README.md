━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 🔄 Rolling Updates & Rollbacks
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Rolling updates and rollbacks allow **zero-downtime application deployments** in Kubernetes.

They ensure continuous availability during application updates.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧠 What are Rolling Updates?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Rolling updates gradually replace old Pods with new ones.

This avoids service interruption during deployments.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## ⏪ What are Rollbacks?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Rollbacks allow reverting to a previous stable version.

They are useful when a deployment update fails.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## ⚙️ How Rolling Updates Work
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Kubernetes updates Pods in batches.

Old Pods are terminated only after new Pods are ready.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 📌 Deployment Strategy
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- maxSurge  
- maxUnavailable  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🌟 Best Practices
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Always monitor deployments  
- Keep rollout history  
- Test updates in staging  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧭 What You Will Learn Next
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Next, you will learn about DaemonSets and StatefulSets.

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
