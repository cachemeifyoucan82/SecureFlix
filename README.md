# SecureFlix
SecureFlix is a Netflix-clone application deployed on AWS EKS with a full DevSecOps pipeline, integrating infrastructure as code, automated security scanning, CI/CD, and observability to demonstrate secure cloud-native application delivery.

**Architecture Diagram**
put here

**#Technology Stack**
Cloud: AWS (EKS, ECR, VPC, IAM)
CI/CD: GitHub Actions, Jenkins
IaC: Terraform
Containers: Docker, Kubernetes
Security: SonarQube, Snyk, Trivy, OWASP ZAP
Monitoring: Prometheus, Grafana, Loki
Language: Python (FastAPI)

**CI/CD Pipeline Flow** (Need to update when finsihed)
Explain in simple steps:
Developer pushes code to GitHub
GitHub Actions runs tests and security scans
Docker images are built and scanned
Images are pushed to Amazon ECR
Jenkins deploys to EKS
OWASP ZAP scans the live application
Deployment is promoted to production
This shows process thinking, not just tooling.

**Security Controls** (Explain what blocks deployments.)
SAST: SonarQube
SCA: Snyk
Container scanning: Trivy
DAST: OWASP ZAP
Kubernetes security best practices enforced

**Monitoring & Logging**
Briefly explain:
What metrics are collected
What dashboards show
What alerts exist

**Project Status:**
This project is for learning and demonstration purposes and does not stream copyrighted content.


