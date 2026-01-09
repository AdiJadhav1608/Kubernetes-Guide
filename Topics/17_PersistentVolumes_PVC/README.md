━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 📦 Persistent Volumes & Persistent Volume Claims
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Persistent Volumes (PV) and Persistent Volume Claims (PVC) provide **durable storage** beyond Pod lifecycles.

They allow storage to exist independently of Pods.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧠 What is a Persistent Volume (PV)?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

A PV is a cluster-wide storage resource.

It is provisioned by an administrator or dynamically by a storage class.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧠 What is a Persistent Volume Claim (PVC)?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

A PVC is a request for storage by a user.

It specifies size, access mode, and storage requirements.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🔁 How PV & PVC Work Together
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

The PVC requests storage.

Kubernetes binds the PVC to a matching PV.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 📦 Access Modes
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- ReadWriteOnce  
- ReadOnlyMany  
- ReadWriteMany  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🌟 Best Practices
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Use dynamic provisioning when possible  
- Define appropriate storage classes  
- Monitor storage usage  

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
