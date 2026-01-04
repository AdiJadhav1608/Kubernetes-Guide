━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 🔁 Kubernetes ReplicaSet
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

ReplicaSet is a Kubernetes object used to maintain a **stable set of running Pods**.

It ensures that a specified number of identical Pods are always running.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧠 What is a ReplicaSet?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

A ReplicaSet continuously monitors Pods.

If a Pod fails or is deleted, ReplicaSet creates a new one automatically.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🎯 Why ReplicaSet is Needed?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Pods are ephemeral and can fail anytime.

ReplicaSet ensures **high availability** by maintaining the desired Pod count.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧱 Key Features of ReplicaSet
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Maintains desired number of Pods  
- Automatically replaces failed Pods  
- Uses label selectors to manage Pods  
- Works behind Deployments  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🔗 Relationship with Deployment
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

ReplicaSet is usually not created directly.

Deployments manage ReplicaSets and provide rolling updates and rollbacks.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🔄 How ReplicaSet Works
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

1. User defines desired replicas  
2. ReplicaSet checks current Pods  
3. Creates or deletes Pods as needed  
4. Maintains the desired state continuously  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧭 What You Will Learn Next
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Next, you will learn how Deployments manage ReplicaSets and application updates.

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
