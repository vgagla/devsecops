
# 🛡️ DevSecOps Project – Secure SDLC & CI/CD Security

## 📌 Overview
This project focuses on implementing a Secure Software Development Lifecycle (Secure SDLC) by integrating security controls across CI/CD pipelines, enabling automated security checks and compliance-ready delivery processes.

---

## 🚀 Key Implementations

### 🔐 Secure SDLC & CI/CD
Implemented a Secure SDLC by integrating security controls into CI/CD pipelines (Jenkins, GitLab), enabling automated security checks and compliance-ready delivery processes.

---

### 🧪 SAST / Code Quality
Integrated static analysis using SonarQube and Fortify to detect vulnerabilities and enforce secure coding standards early in the development lifecycle.

---

### 🌐 DAST / Runtime Testing
Performed dynamic security testing using OWASP ZAP to identify OWASP Top 10 vulnerabilities in web applications and APIs during staging phases.

---

### 📦 SCA / Supply Chain Security
Implemented dependency scanning with OWASP Dependency-Check to identify CVEs in third-party libraries and reduce open-source risk.

---

### 🐳 Container & Kubernetes Security
Secured containerized workloads using Trivy, enforced Kubernetes security with Kubesec and kube-bench, and implemented runtime protection via Falco and service mesh security with Istio.

---

### ⚙️ Infrastructure & Compliance
Applied Policy-as-Code using Open Policy Agent (OPA), secured Infrastructure as Code (Terraform), and implemented compliance validation using Chef InSpec to meet regulatory requirements (e.g., DORA).

---

## 🎯 Outcome
- Automated end-to-end security in CI/CD pipelines  
- Early detection of vulnerabilities (Shift-Left Security)  
- Improved compliance and audit readiness  
- Enhanced container and Kubernetes security posture  
- Standardized and scalable DevSecOps practices  

---
### NodeJS Microservice - Docker Image -

`docker run -p 8787:5000 siddharth67/node-service:v1`

`curl localhost:8787/plusone/99`
 
### NodeJS Microservice - Kubernetes Deployment -
`kubectl create deploy node-app --image siddharth67/node-service:v1`

`kubectl expose deploy node-app --name node-service --port 5000 --type ClusterIP`

`curl node-service-ip:5000/plusone/99`
