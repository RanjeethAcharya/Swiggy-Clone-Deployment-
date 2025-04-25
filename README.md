# Swiggy-Clone-Deployment
Deploying using Terraform, Jenkins, ArgoCD, and AWS EKS
![image](https://github.com/user-attachments/assets/b96c6124-3c7f-4ab6-9470-15f042e2167e)


**Jenkins plugins must install**
- Eclipse temurin
- sonarqube scanner
- nodejs
- Owasp
- Docker and Docker Commons, Docker pipeline

**Manage Jenkins > tools **Configuration**
- **jdk17**            : jdk-17.0.11+9
- **sonarqube**        : default version
- **nodejs16**         : NodeJS 16.20.2
- **docker**           : Latest
- Dependency-Check
  **DC**               : install automatically 

**After completing CI task, Start setting up AWS CLI, Kubectl, EKSCTL and ArgoCD**

Install the below given links

- AWSCLI  : https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
- Kubectl : https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/ 
- EKSCTL  : https://eksctl.io/installation/

For ArgoCD installation refer below given README file
https://github.com/RanjeethAcharya/Swiggy-Clone-Deployment-/blob/main/ArgoCD/README.md
(https://github.com/RanjeethAcharya/Swiggy-Clone-Deployment-/blob/main/ArgoCD/README.md)
