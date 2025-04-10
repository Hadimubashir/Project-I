# 📺 Amazon Prime Clone Deployment Project

### CI/CD Pipeline with EKS, Terraform, Jenkins, and ArgoCD

---

## 🚀 Overview

This project demonstrates the deployment of an Amazon Prime clone using modern DevOps practices. It features end-to-end automation of infrastructure provisioning, application build, security scanning, containerization, and deployment with real-time monitoring.

---

## 🛠️ Tools & Technologies

- **Infrastructure & Cloud:** Terraform, AWS (EKS, EC2, ECR, IAM)
- **CI/CD & Source Control:** Jenkins, GitHub, ArgoCD
- **Build & Analysis:** NodeJS (NPM), SonarQube, Aqua Trivy
- **Containerization:** Docker
- **Monitoring:** Prometheus, Grafana
- **Others:** Helm, AWS CLI, Kubectl, Eksctl

---

## 🧩 Key Implementations

1. **Provisioned AWS Infrastructure**  
   - Created EC2 and EKS clusters using **Terraform** for a scalable and automated environment.

2. **CI/CD Integration**  
   - Integrated **GitHub** with **Jenkins** to automate pipeline triggering on code changes.

3. **Jenkins Pipeline Configuration**  
   - Pipeline stages included:
     - Git Checkout  
     - Static Code Analysis with **SonarQube**  
     - Dependency Installation with **NPM**  
     - Security Scan with **Aqua Trivy**

4. **Dockerization & Image Management**  
   - Built Docker images and pushed them to **AWS ECR** via Jenkins.

5. **Continuous Deployment**  
   - Deployed the application on **EKS** using **ArgoCD**, enabling GitOps workflow.

6. **Monitoring & Alerting**  
   - Deployed **Prometheus** and **Grafana** using **Helm** for monitoring Kubernetes cluster and application metrics.

---


---

## 📌 Conclusion

This project showcases strong hands-on experience in cloud infrastructure provisioning, CI/CD pipeline creation, container orchestration with Kubernetes, and monitoring using modern DevOps tools.

---

> ⭐️ Star this repo if you find it helpful!
