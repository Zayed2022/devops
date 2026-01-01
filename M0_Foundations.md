# 📦 MODULE 0 – Foundations (DevOps for Freshers)

> **Goal:**
> Build a strong **industry mental model** before touching tools.
> Understand **what DevOps is**, **how software is built**, and **what companies expect**.

---

## 📌 What is DevOps?

![Image](https://www.simform.com/wp-content/uploads/2022/01/what-is-devops-lifecycle.png)

![Image](https://www.slideteam.net/media/catalog/product/cache/1280x720/k/e/key_pillars_of_successful_devops_strategy_slide01.jpg)

![Image](https://media.licdn.com/dms/image/v2/D4D12AQFkNMFq37__mg/article-cover_image-shrink_600_2000/article-cover_image-shrink_600_2000/0/1674753638284?e=2147483647\&t=Hlna6Z4JLMoIjQegRMckCmwZMdSq4jtczj0KQvcDyek\&v=beta)

**DevOps** is a **culture and set of practices** that improves an organization’s ability to:

* Build
* Test
* Release
* Monitor

applications **faster and more reliably**.

### 🎯 Goal of DevOps

* Increase **speed**
* Improve **efficiency**
* Deliver **high-quality software**
* Reduce **manual effort**
* Enable **frequent releases**

> DevOps is **NOT just tools** – it’s about **collaboration + automation + feedback**.

---

## 🏛️ Four Pillars of DevOps

![Image](https://www.leapwork.com/hs-fs/hubfs/Blog%20Images/DevOps-pipeline.png?height=743\&name=DevOps-pipeline.png\&width=1251)

![Image](https://razorops.com/images/blog/4-pillars-of-successful-devops-assessment.webp)

### 1️⃣ Automation

* Reduces manual work
* Increases delivery speed
* Used in:

  * CI/CD pipelines
  * Infrastructure provisioning
  * Testing & deployments

### 2️⃣ Quality

* Ensure product quality at every stage
* Shift-left testing
* Automated tests in pipelines

### 3️⃣ Continuous Testing

* Testing happens continuously
* Unit → Integration → Security tests
* Bugs are caught early

### 4️⃣ Continuous Monitoring & Observability

* Monitor systems & applications
* Metrics, logs, alerts
* Helps detect issues before customers do

---

## 🔄 SDLC (Software Development Life Cycle)

![Image](https://datarob.com/content/images/2019/08/SDLC-stages.png)

![Image](https://agilefirst.io/content/images/2022/06/agile-devops.png)

SDLC is a **standard process followed by the software industry** to manage:

* Design
* Development
* Testing
* Deployment

### 🎯 Goal of SDLC

Deliver a **high-quality product** to customers in a structured way.

---

### 🔁 SDLC Stages (with Roles)

| Stage         | Activity                  | Roles              |
| ------------- | ------------------------- | ------------------ |
| 1. Planning   | Requirement gathering     | BA, PM, PO         |
| 2. Defining   | Requirement documentation | BA, PO             |
| 3. Designing  | HLD & LLD                 | Solution Architect |
| 4. Building   | Code + Infra              | Dev, DevOps, DBA   |
| 5. Testing    | Validate product          | QA, DevOps         |
| 6. Deployment | Release to prod           | DevOps, SRE        |

📌 **DevOps is involved from Build → Deployment → Monitoring**

---

## 🏢 Organizational Roles in IT Projects

![Image](https://alcor-bpo.com/wp-content/uploads/2024/01/VP_engineering_11zon_2.jpg)

![Image](https://miro.medium.com/v2/resize%3Afit%3A1400/1%2AGqSZiwLOkoGSAiwdxElOYA.jpeg)

### 👤 Customer

* Provides:

  * Requirements
  * Feedback
  * Feature requests

---

### 👤 Business Analyst (BA)

* Interacts with customers
* Gathers requirements
* Creates **BRD (Business Requirement Document)**

---

### 👤 Product Manager

* Prioritizes requirements based on:

  * Business goals
  * Market analysis
  * Organization capacity

---

### 👤 Product Owner (PO)

* Converts requirements into **Epics**
* Manages **Product Backlog**
* Defines **acceptance criteria**

---

### 👤 Solution Architect (SA)

* Designs:

  * **HLD (High-Level Design)**
  * **LLD (Low-Level Design)**
* Ensures:

  * Feasibility
  * Scalability
  * Resource availability

---

### 👨‍💻 Development Teams

* Developers
* DevOps Engineers
* QA Engineers
* DBAs
* Testers

All teams **collaborate closely** in DevOps.

---

### 🔧 DevOps Engineer Responsibilities

* Infrastructure setup (VMs, Kubernetes, Cloud)
* CI/CD automation
* Testing & deployment automation
* Security integration in pipelines
* Monitoring & reliability

---

### 🔁 SRE (Site Reliability Engineer)

* Ensures system reliability
* Creates dashboards & alerts
* Handles incidents
* Improves system availability

---

## 📋 Project Management with Jira

![Image](https://images.ctfassets.net/xjcz23wx147q/50BUb6V5q7VKH9P5qcCkqO/a115bed3950cd57c087e50bfa10bab3a/scrum-board.png)

![Image](https://images.ctfassets.net/xjcz23wx147q/2v1GpQWUJeioxTPskWvwgW/450973fe7e4fa14254c6bb0bab26a309/epics-vs-stories-agile-development.png)

**Jira** is used to:

* Track work
* Provide visibility to management & stakeholders

### 🔹 Epics

* Large deliverables created by Product Owner
* Example:

  > *Create Kubernetes cluster*

---

### 🔹 Stories / Tasks

* Epic is broken into smaller tasks
* Example:

  * Create EC2
  * Install Docker
  * Configure Kubernetes

---

### 🔹 Scrum & Sprints

* Scrum framework divides work into **Sprints (2–3 weeks)**
* Sprint Planning:

  * Team selects tasks from backlog
* Status tracking:

  * TODO
  * In Progress
  * In Review
  * Done

---

## ☁️ Cloud Computing Basics

![Image](https://media.geeksforgeeks.org/wp-content/uploads/20220311125753/CloudComputing.jpg)

![Image](https://res.cloudinary.com/lwgatsby/f_auto/www/uploads/2021/01/cloudservicemodels2.011421.png)

**Cloud Computing** = Providing IT resources like:

* Servers
* Storage
* Databases

over the **internet** instead of owning physical hardware.

---

### ✅ Benefits of Cloud

* Faster time to market
* Scalability & flexibility
* Cost savings
* Better collaboration

---

### 🔑 5 Core Characteristics

1. On-demand self-service
2. Broad network access
3. Resource pooling
4. Scalability
5. Pay-as-you-go model

---

## 🧱 Cloud Service Models

![Image](https://www.zscaler.com/cxorevolutionaries/sites/default/files/images/blogs/Diagram-OG%402x_0.jpg)

![Image](https://learn.microsoft.com/en-us/azure/security/fundamentals/media/shared-responsibility/shared-responsibility.svg)

### 1️⃣ IaaS (Infrastructure as a Service)

* Provider manages:

  * Hardware
  * Virtualization
* User manages:

  * OS
  * Applications
  * Data

📌 Example: **AWS EC2**

---

### 2️⃣ PaaS (Platform as a Service)

* Provider manages:

  * Infra
  * OS
  * Middleware
  * Runtime
* User manages:

  * Applications
  * Data

📌 Example: **AWS Elastic Beanstalk, Heroku**

---

### 3️⃣ SaaS (Software as a Service)

* Provider manages **everything**
* User manages only:

  * Data
  * Configurations

📌 Example: **Salesforce**

---

## 🌍 Cloud Deployment Models

![Image](https://cdn.prod.website-files.com/6305e59e1a8fa3e7f5f8e555/670fab2ec79bdba488cc7061_cloud2-900x900.png)

![Image](https://media.geeksforgeeks.org/wp-content/uploads/20211123123930/Group2-660x330.jpg)

### ☁️ Public Cloud

* Shared infrastructure
* Example: AWS

### 🏢 Private Cloud

* Dedicated infra for one organization
* On-prem or hosted

### 🔀 Hybrid Cloud

* Combination of public + private

### 🌐 Multi-Cloud

* Uses multiple cloud providers

---

## 🎯 What Companies Expect from a DevOps Engineer (Fresher)

* Strong **Linux basics**
* Cloud fundamentals
* CI/CD understanding
* Automation mindset
* Monitoring awareness
* Willingness to learn continuously
* Collaboration skills

---

## 📦 Tools Used in Real Companies (Preview)

* Linux
* Git & GitHub
* Docker
* Kubernetes
* Jenkins / GitHub Actions
* AWS / Azure / GCP
* Terraform
* Prometheus & Grafana

(We’ll learn these **step by step**)

---

## ✅ Module 0 Summary

✔ Industry mental model
✔ DevOps fundamentals
✔ SDLC & Agile understanding
✔ Cloud basics
✔ Roles & responsibilities clarity

---


