# 🚀 Java CI/CD Pipeline with Security Scans (DevSecOps)

## 📌 Overview
This project demonstrates a Java Maven application with a CI/CD pipeline using GitHub Actions, including security scanning using Trivy and Gitleaks.

---

## 🛠️ Tech Stack
- Java (JDK 17)
- Maven
- GitHub Actions
- Trivy
- Gitleaks

---

## 📂 Project Structure

java-ci-cd-security-pipeline/
- pom.xml
- src/
  - main/
    - java/
      - com/
        - example/
          - HelloWorld.java
- .github/
  - workflows/
    - maven-build.yml
- README.md

---

## ⚙️ How It Works

1. Code is pushed to repository  
2. GitHub Actions triggers workflow  
3. Maven builds the project  
4. Trivy scans for vulnerabilities  
5. Gitleaks scans for secrets  

---

## ▶️ Run Locally

mvn clean compile  
java -cp target/classes com.example.HelloWorld  

---

## 🔐 Security Features

- Trivy → vulnerability scanning  
- Gitleaks → detects secrets in code  

---

## 🚀 Future Improvements

- Add deployment stage  
- Add Docker integration  
- Add testing  
