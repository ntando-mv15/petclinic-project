# Java Petclinic - CI/CD Pipeline with SonarQube 

This project automates the **build, test, quality analysis, and deployment** of a Java-based **Petclinic application** using **GitHub Actions** and **SonarQube** for code quality and security checks.  

---

## 📌 Project Overview  

This project builds on a **fully automated CI/CD pipeline** by integrating **SonarQube**, a powerful tool for **code quality analysis and security scanning**.  

### Key Features:
- **CI/CD with GitHub Actions** - Automates build, test, and deployment.  
- **SonarQube Integration** - Ensures high code quality and security.  
- **Automated Static Code Analysis** - Identifies bugs, vulnerabilities, and code smells.  
- **Deployment to EC2** - The final application runs on an AWS EC2 Tomcat server.
  
---

### CI/CD Workflow (GitHub Actions)  

Each time you push code, GitHub Actions:  
1. **Builds & Tests the Java Application** 
2. **Runs SonarQube Analysis**   
3. **Pushes the Image to Docker Hub (or ECR)**   
4. **Deploys the Application to Tomcat Server hosted on EC2**

## Project Documentation
Find detailed project documentation here:
[Integrating Sonarqube Medium Article](https://medium.com/@ntando.mv15/integrating-sonarqube-in-ci-cd-with-github-actions-ee6ce450ceea)
