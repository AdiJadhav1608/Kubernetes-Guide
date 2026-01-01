━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 🏗️ Kubernetes Architecture
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Kubernetes architecture defines how different components work together to manage containerized applications efficiently.

It follows a **master–worker (control plane–node)** model.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧠 High-Level Architecture Overview
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Kubernetes consists of a Control Plane and Worker Nodes.

Each component has a specific responsibility to maintain cluster health.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🎛️ Control Plane Components
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

The Control Plane manages the overall state of the cluster.

It makes global decisions such as scheduling and scaling.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
### 📌 kube-apiserver
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Acts as the front-end of the Kubernetes cluster.

All requests (kubectl, UI, API) go through the API Server.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
### 📌 etcd
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

A distributed key-value store.

Stores cluster state, configuration, and metadata.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
### 📌 kube-scheduler
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Assigns Pods to suitable worker nodes.

Considers resource availability and constraints.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
### 📌 kube-controller-manager
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Runs controller processes.

Ensures desired state matches the current state.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🖥️ Worker Node Components
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Worker nodes run the actual application workloads.

They host Pods and containers.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
### 📌 kubelet
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Agent running on each worker node.

Communicates with the API Server and manages Pods.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
### 📌 kube-proxy
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Handles networking and service communication.

Manages IP tables and traffic routing.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
### 📌 Container Runtime
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Responsible for running containers.

Examples include containerd and CRI-O.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🔄 Architecture Workflow
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

1. User submits a request using kubectl  
2. API Server validates the request  
3. Scheduler assigns a node  
4. Kubelet creates the Pod  
5. kube-proxy enables networking  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🌟 Why Architecture Matters
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Understanding architecture helps in troubleshooting.

It is essential for production-grade Kubernetes usage.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧭 What You Will Learn Next
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Next, you will learn how to install and set up Kubernetes using different tools.

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
