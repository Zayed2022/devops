# DevOps 2026 Roadmap
*Based on the guide by Abhishek Veeramalla*

## Phase 1: Fundamentals (25 Days)
Build the core foundation of software delivery and environment management.

* **DevOps Philosophy:** Understand the "What" and "Why" of DevOps and its role in the SDLC.
* **Linux Basics:** Focus on SSH protocol, virtual machines, and the **Top 50 shell commands**.
* **Version Control:** Git & GitHub basics, branching strategies, and AI-assisted coding.
* **Containers (Docker):** Architecture, networking, volumes, and multi-stage builds.
* **Kubernetes (K8s):** Architecture, Pods, Deployments, Helm, and Ingress.
* **CI/CD Foundation:** GitHub Actions for CI and Argo CD for GitOps-style delivery.

---

## Phase 2: Cloud Mastery - AWS or Azure (25 Days)
Master one major cloud provider. Do not try to learn both at once.

* **IAM:** Identity & Access Management, roles, and permissions.
* **Compute:** EC2, Auto-scaling groups, and Load Balancers.
* **Networking:** VPC, Route 53, and Security Groups.
* **Storage & DB:** S3 buckets and RDS (Managed Databases).
* **Managed Services:** EKS (Kubernetes) and ECR (Container Registry).

---

## Phase 3: Advanced Infrastructure as Code (10 Days)
Automate your infrastructure scaling and management.

* **Terraform:** State management, state locking, and providers.
* **Modularization:** Creating reusable modules and managing workspaces.
* **Advanced Ops:** Drift detection and importing existing resources.

---

## Phase 4: Python for Automation (10 Days)
Learn Python specifically for DevOps tasks, not general app dev.

* **Core Logic:** Data types, modules, and exception handling.
* **Boto3:** Using Python to automate AWS/Cloud infrastructure.
* **Projects:** Real-time automation scripts for day-to-day operations.

---

## Phase 5: AI-Assisted DevOps (10 Days)
Leverage GenAI to speed up your workflow—essential for 2026.

* **Prompt Engineering:** Techniques for zero-shot and multi-shot prompting.
* **Local AI:** Running models locally with Ollama.
* **AI Agents:** Building automation agents using Crew AI.

---

## Phase 6: Observability (5-6 Days)
Monitor and maintain healthy systems.

* **Monitoring:** Prometheus & Grafana for metrics and visualization.
* **Logging:** ELK Stack (Elasticsearch, Logstash, Kibana).
* **Tracing:** OpenTelemetry and Jaeger.
* **Incident Response:** PagerDuty for on-call management.

---
*Created as a study guide for 2026 DevOps Aspirants.*


# DevOps 2026: Project-Based Roadmap

---

## Phase 1: Fundamentals (25 Days)
**Concepts:** Linux, Git, Docker, Kubernetes Basics  

**Project:** *The Containerized Web App*  
- **Task:** Take a simple Python/Node.js app, write a Dockerfile using multi-stage builds to keep it small, and push it to GitHub.  
- **Sub-task:** Deploy that container into a local Kubernetes cluster (Minikube/Kind) using a Deployment and a Service.  
- **Key Skill:** Containerizing apps and K8s orchestration  

---

## Phase 2: Cloud Mastery - AWS/Azure (25 Days)
**Concepts:** IAM, VPC, EC2, S3, Managed K8s (EKS/AKS)  

**Project:** *Highly Available Static Website*  
- **Task:** Host a website on S3/Blob Storage but secure it behind a CloudFront/CDN with an SSL certificate.  
- **Sub-task:** Set up a VPC with private subnets and a Bastion Host to securely access a private EC2 instance.  
- **Key Skill:** Cloud networking and security  

---

## Phase 3: Infrastructure as Code (10 Days)
**Concepts:** Terraform Modules, State, Providers  

**Project:** *Infrastructure-in-a-Box*  
- **Task:** Write Terraform code to deploy an entire production environment (VPC, 2 EC2 instances, and an RDS Database).  
- **Sub-task:** Use Terraform Modules so you can deploy a "Dev" and "Prod" environment using the same code but different variables.  
- **Key Skill:** Reusable, modular automation  

---

## Phase 4: Python for DevOps (10 Days)
**Concepts:** Boto3, Automation Scripts, APIs  

**Project:** *The Cost-Saver Bot*  
- **Task:** Write a Python script using Boto3 (for AWS) that identifies all unattached EBS volumes or underutilized EC2 instances and sends a report to Slack/Email.  
- **Sub-task:** Schedule this script to run every Sunday using a Cron job or AWS Lambda.  
- **Key Skill:** Cloud cost optimization through code  

---

## Phase 5: AI-Assisted DevOps (10 Days)
**Concepts:** Ollama, Crew AI, Prompt Engineering  

**Project:** *The AI Site Reliability Engineer (SRE)*  
- **Task:** Use Crew AI to build an AI Agent that can read a Kubernetes error log and suggest a fix (Prompt Engineering).  
- **Sub-task:** Use Ollama to run a local Llama 3 model to summarize your daily GitHub commits into a "Daily Standup" report.  
- **Key Skill:** Integrating LLMs into operational workflows  

---

## Phase 6: Observability (5–6 Days)
**Concepts:** Prometheus, Grafana, ELK, PagerDuty  

**Project:** *The Full-Stack Dashboard*  
- **Task:** Install Prometheus and Grafana on your K8s cluster. Create a dashboard that tracks CPU/Memory usage of your apps.  
- **Sub-task:** Set up an Alert Manager rule: If an app goes down, trigger a notification (simulated PagerDuty or Slack alert).  
- **Key Skill:** Proactive system monitoring  

---

## Final Capstone Project: *The Resume Builder*
**Project:** *End-to-End GitOps Pipeline*  
- **Code:** Push a change to GitHub.  
- **CI:** GitHub Actions builds the Docker image and scans it for vulnerabilities.  
- **IaC:** Terraform sets up an EKS Cluster.  
- **CD:** Argo CD detects the new image and automatically deploys it to EKS.  
- **Monitor:** Grafana shows the live traffic to the new deployment.  
