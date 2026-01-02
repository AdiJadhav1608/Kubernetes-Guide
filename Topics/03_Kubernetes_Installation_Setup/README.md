━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 🛠️ Kubernetes Installation & Setup
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Kubernetes can be installed using different tools based on learning or production needs.

This section covers both **local development** and **production-grade** installation methods.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧠 Installation Methods Overview
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Kubernetes installation methods vary by use case.

Beginners usually start locally, while production uses multi-node clusters.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 💻 Minikube (Local Cluster)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Minikube is used to run Kubernetes locally.

It is ideal for learning, testing, and development.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
### ✅ Features of Minikube
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Single-node Kubernetes cluster  
- Easy to install and manage  
- Supports addons like dashboard and ingress  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
### ⚙️ Basic Minikube Commands
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Start cluster  
  `minikube start`

- Check status  
  `minikube status`

- Stop cluster  
  `minikube stop`

- Delete cluster  
  `minikube delete`

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🏗️ kubeadm (Production Setup)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

kubeadm is used to create production-ready Kubernetes clusters.

It supports multi-node and high-availability setups.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
### ✅ Features of kubeadm
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Production-grade clusters  
- Full control over configuration  
- Supports HA control plane  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
### ⚙️ Basic kubeadm Workflow
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

1. Install container runtime  
2. Install kubeadm, kubelet, kubectl  
3. Initialize control plane  
4. Join worker nodes  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 📂 Folder Structure Explanation
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- `minikube/`  
  Contains Minikube-specific setup notes or commands

- `kubeadm/`  
  Contains kubeadm installation steps and configuration

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🎯 When to Use What?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Use **Minikube** for learning and local testing  
- Use **kubeadm** for real-world and production environments  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧭 What You Will Learn Next
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Next, you will learn how to interact with Kubernetes using kubectl commands.

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
