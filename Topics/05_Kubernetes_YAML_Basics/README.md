━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 📄 Kubernetes YAML Basics
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

YAML is the primary format used to define Kubernetes resources.

It describes the desired state of objects such as Pods, Deployments, and Services.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧠 What is YAML?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

YAML stands for YAML Ain’t Markup Language.

It is a human-readable data serialization format used for configuration files.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🎯 Why Kubernetes Uses YAML?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Kubernetes uses YAML to define and manage resources declaratively.

It enables version control, automation, and repeatable deployments.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧱 Basic Structure of a Kubernetes YAML File
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Every Kubernetes YAML file follows a standard structure.

This structure helps Kubernetes understand what to create and how.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧩 Key YAML Fields
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- apiVersion  
  Specifies the Kubernetes API version

- kind  
  Defines the resource type such as Pod or Deployment

- metadata  
  Stores name, labels, and annotations

- spec  
  Defines the desired state of the resource

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 📌 Sample Kubernetes YAML
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

apiVersion: v1  
kind: Pod  
metadata:  
  name: sample-pod  
spec:  
  containers:  
  - name: nginx  
    image: nginx  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## ⚠️ YAML Indentation Rules
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

YAML depends on correct indentation.

Spaces must be used instead of tabs.

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 📂 Multi-Document YAML Files
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Multiple Kubernetes resources can be defined in one file.

They are separated using three dashes (---).

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## ✅ Kubernetes YAML Best Practices
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Use consistent indentation  
- Keep YAML files readable  
- Use meaningful names  
- Avoid unnecessary fields  

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## 🧭 What You Will Learn Next
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Next, you will learn about Kubernetes objects and their role in the cluster.

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
