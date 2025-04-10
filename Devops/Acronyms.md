---

### 🔧 **Core AWS Services (Cloud Basics)**

1. **AWS (Amazon Web Services)**  
   - **What**: Cloud platform offering servers, storage, databases, etc.  
   - **When/How**: Use to host websites, store files, build APIs, run VMs.

2. **EC2 (Elastic Compute Cloud)**  
   - **What**: Virtual machine in AWS.  
   - **When/How**: Spin up EC2 when you need a server (e.g., backend app, DB host).

3. **S3 (Simple Storage Service)**  
   - **What**: File/object storage.  
   - **When/How**: Store static files, backups, images. Pay-per-use.

4. **VPC (Virtual Private Cloud)**  
   - **What**: Isolated network in AWS.  
   - **When/How**: Secure your resources—set subnets, route tables, firewalls.

5. **IAM (Identity and Access Management)**  
   - **What**: Manages users and permissions.  
   - **When/How**: Control who can access what in AWS (least privilege principle).

6. **RDS (Relational Database Service)**  
   - **What**: Managed SQL databases (MySQL, PostgreSQL, etc.).  
   - **When/How**: When you want a database but don’t want to manage updates/backups.

7. **EBS (Elastic Block Store)**  
   - **What**: Disk volumes for EC2 instances.  
   - **When/How**: Like a hard drive for your EC2 server.

8. **ELB (Elastic Load Balancer)**  
   - **What**: Distributes traffic to multiple servers.  
   - **When/How**: Use to handle high traffic and avoid single points of failure.

9. **Lambda**  
   - **What**: Serverless function execution.  
   - **When/How**: Run code without a server (e.g., triggered by S3 upload or API call).

---

### 📦 **Messaging, Security & Infra**

10. **SQS (Simple Queue Service)**  
    - **What**: Message queuing between services.  
    - **When/How**: For microservices or decoupled apps—queue tasks like emails.

11. **SNS (Simple Notification Service)**  
    - **What**: Pub/sub messaging.  
    - **When/How**: Send notifications to email, SMS, other services.

12. **KMS (Key Management Service)**  
    - **What**: Manages encryption keys.  
    - **When/How**: Encrypt S3 data, DB, etc. without writing encryption code.

13. **CFN (CloudFormation)**  
    - **What**: Infra as code for AWS (YAML/JSON templates).  
    - **When/How**: Use to automate provisioning of resources (repeatable setups).

14. **CLI (Command Line Interface)**  
    - **What**: AWS commands in terminal.  
    - **When/How**: Automate or script AWS operations.

15. **SDK (Software Development Kit)**  
    - **What**: Code libraries for AWS in Python, JS, etc.  
    - **When/How**: Use in apps to interact with AWS (e.g., upload to S3).

---

### 🔁 **DevOps + CI/CD**

1. **CI/CD (Continuous Integration/Delivery/Deployment)**  
   - **What**: Automate testing and deployment of code.  
   - **When/How**: After push to GitHub, trigger builds, tests, and production deployment (e.g., via Jenkins or GitHub Actions).

2. **IaC (Infrastructure as Code)**  
   - **What**: Define infrastructure in code (e.g., Terraform).  
   - **When/How**: Reusable, version-controlled cloud infrastructure setups.

3. **DORA (DevOps Research & Assessment)**  
   - **What**: Research on DevOps metrics (e.g., deployment frequency, MTTR).  
   - **When/How**: Use to measure DevOps maturity.

4. **SLI/SLO/SLA**  
   - **SLI**: What you measure (e.g., uptime).  
   - **SLO**: Your target (e.g., 99.9% uptime).  
   - **SLA**: The legal agreement with clients.

---

### 🐧 **Linux Essentials**

1. **GNU/Linux**  
   - **GNU**: Open-source OS tools.  
   - **Linux**: Kernel. Combined they form operating systems like Ubuntu.

2. **CLI** vs **GUI**  
   - CLI: Terminal; GUI: Desktop apps.  
   - When scripting or configuring servers, always use CLI.

3. **TTY**  
   - **What**: Virtual terminal.  
   - **When/How**: You see `/dev/tty` in server access logs or sessions.

4. **FHS (Filesystem Hierarchy Standard)**  
   - **What**: Folder structure rules in Linux (`/bin`, `/etc`, `/var`).  
   - **When/How**: Helps locate system files during dev/debugging.

5. **rpm/dpkg**  
   - **What**: Package managers.  
   - **When/How**: Use `rpm` on Red Hat/CentOS; `dpkg` on Debian/Ubuntu.

---

### 🐍 **Python Concepts**

1. **PEP**  
   - **What**: Python design proposals.  
   - **Famous**: PEP8 (code style), PEP484 (type hints).

2. **GIL (Global Interpreter Lock)**  
   - **What**: Only one thread runs at a time in CPython.  
   - **When/How**: Impacts multi-threading performance.

3. **ORM (Object-Relational Mapping)**  
   - **What**: Code-first DB access (e.g., SQLAlchemy, Django ORM).  
   - **When/How**: No SQL writing—just Python classes.

4. **PyPI**  
   - **What**: Python package repo (`pip install flask`).  
   - **When/How**: All 3rd-party libraries come from here.

---

### 🐳 **Containers & K8s**

1. **Docker**  
   - **What**: Containerization platform.  
   - **When/How**: Use for portable, isolated environments (e.g., run apps without conflicts).

2. **Kubernetes (K8s)**  
   - **What**: Orchestrator for managing containers at scale.  
   - **When/How**: Automatically handles deployment, scaling, healing.

3. **CIDR / CNI**  
   - CIDR: IP range format (used in networking).  
   - CNI: How containers get IPs and networking.

---

### 📊 **Monitoring & Infra**

1. **Prometheus**  
   - **What**: Time-series DB for monitoring.  
   - **When/How**: Use with Grafana for alerts, metrics dashboards.

2. **Grafana**  
   - **What**: Dashboard for visualizing metrics.  
   - **When/How**: Use to monitor CPU, memory, app performance visually.

3. **Terraform**  
   - **What**: IaC tool (multi-cloud).  
   - **When/How**: Use to deploy AWS, Azure, GCP resources via `.tf` files.

---

### 📁 **Build Tools & Git**

1. **VCS / Git / DVCS**  
   - **What**: Track changes in code. Git is a DVCS.  
   - **When/How**: Every developer uses this. GitHub hosts repos.

2. **PR (Pull Request)**  
   - **What**: Suggest and review changes before merge.  
   - **When/How**: Always create PRs in team environments.

3. **SHA**  
   - **What**: Unique ID for Git commits.  
   - **When/How**: Helps trace code changes.

---
