━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 📂 Kubernetes Namespaces
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Namespaces are used to **logically isolate resources** within a Kubernetes cluster.

They help organize and manage resources in large or multi-team environments.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧠 What is a Namespace?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

A Namespace is a virtual cluster inside a Kubernetes cluster.

It provides separation for resources without creating multiple clusters.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🎯 Why Use Namespaces?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Namespaces help avoid naming conflicts.

They improve resource organization, security, and access control.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧱 Common Use Cases
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Separating environments (dev, test, prod)  
- Multi-team resource isolation  
- Applying resource quotas and RBAC  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 📌 Default Namespaces
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Kubernetes comes with predefined namespaces.

Examples include default, kube-system, and kube-public.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🔐 Namespaces and Security
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

RBAC and ResourceQuota are usually applied at namespace level.

This helps control access and resource usage.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧭 What You Will Learn Next
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Next, you will learn how Services expose applications in Kubernetes.

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
