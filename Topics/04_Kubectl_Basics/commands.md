━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 🖥️ Kubectl Commands Cheat Sheet
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

This file contains essential kubectl commands used for daily Kubernetes operations.

It is useful for quick revision and hands-on practice.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🔍 Cluster Information
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Check cluster info  
  `kubectl cluster-info`

- Check nodes  
  `kubectl get nodes`

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 📦 Pod Management
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- List pods  
  `kubectl get pods`

- Describe pod  
  `kubectl describe pod <pod-name>`

- Delete pod  
  `kubectl delete pod <pod-name>`

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🚀 Deployment Management
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- List deployments  
  `kubectl get deployments`

- Describe deployment  
  `kubectl describe deployment <deployment-name>`

- Scale deployment  
  `kubectl scale deployment <name> --replicas=3`

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🌐 Service Management
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- List services  
  `kubectl get svc`

- Describe service  
  `kubectl describe svc <service-name>`

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 📄 YAML & Configuration
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Apply YAML file  
  `kubectl apply -f file.yaml`

- Delete using YAML  
  `kubectl delete -f file.yaml`

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🛠️ Debugging & Logs
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- View logs  
  `kubectl logs <pod-name>`

- Execute command inside pod  
  `kubectl exec -it <pod-name> -- /bin/bash`

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧹 Cleanup Commands
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Delete all pods  
  `kubectl delete pods --all`

- Delete all resources in namespace  
  `kubectl delete all --all`

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
