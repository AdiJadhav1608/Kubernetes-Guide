━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 🌐 Kubernetes Services
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Kubernetes Services provide a **stable network endpoint** to access Pods.

They enable communication between different components inside and outside the cluster.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧠 What is a Service?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

A Service is an abstraction that exposes a set of Pods.

It uses labels to dynamically route traffic to healthy Pods.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🎯 Why Services are Needed?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Pods are ephemeral and their IPs change frequently.

Services provide a stable IP and DNS name for communication.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧱 Types of Kubernetes Services
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- ClusterIP  
- NodePort  
- LoadBalancer  

Each type serves a different access requirement.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🔗 ClusterIP
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Exposes the service internally within the cluster.

Used for internal communication between applications.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🚪 NodePort
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Exposes the service on each Node’s IP and a static port.

Allows external access using `<NodeIP>:<NodePort>`.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## ☁️ LoadBalancer
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Creates an external load balancer.

Used mainly in cloud environments for production workloads.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧭 What You Will Learn Next
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Next, you will learn how Labels and Selectors work in Kubernetes.

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
