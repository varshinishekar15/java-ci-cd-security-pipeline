# 🚀 Java CI/CD Pipeline with Security Scans (DevSecOps)

This project demonstrates how to build a Java Maven application and implement a CI/CD pipeline with integrated security scanning using GitHub Actions.

---

## 📌 Overview

This project implements a DevSecOps pipeline:

- ☕ Java application built using Maven  
- ⚙️ CI pipeline using GitHub Actions  
- 🔐 Security scanning using Trivy and Gitleaks  
- 🔄 Automated workflow on every push  

---

## 🛠️ Tech Stack

- Java (JDK 17)
- Maven
- GitHub Actions
- Trivy (Security Scanner)
- Gitleaks (Secrets Detection)

---

## 📂 Project Structure

```text
java-ci-cd-security-pipeline/
├── pom.xml
├── src/
│   └── main/
│       └── java/
│           └── com/
│               └── example/
│                   └── HelloWorld.java
├── .github/
│   └── workflows/
│       └── maven-build.yml
└── README.md

---

## ⚙️ How It Works

1. Code is pushed to repository  
2. GitHub Actions triggers workflow  
3. Maven builds the project  
4. Trivy scans for vulnerabilities  
5. Gitleaks scans for secrets  

---

## ▶️ Run Locally

```bash
mvn clean compile
java -cp target/classes com.example.HelloWorld
