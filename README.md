# DevOps + Cloud AWS + MERN Interview Roadmap

This repository is my structured revision workspace for:

- MERN Stack fresher interviews
- DevOps fundamentals
- AWS cloud services
- CI/CD, containers, orchestration, IaC, and monitoring

## Connect With Me

- Portfolio: [devops-portfolio-kappa.vercel.app](https://devops-portfolio-kappa.vercel.app/)
- LinkedIn: [shahe-alam-6a552b320](https://www.linkedin.com/in/shahe-alam-6a552b320/)
- GitHub: [WebXWizard](https://github.com/WebXWizard)

Main revision vaults:

- `MERN-Revision`
- `MERN Stack Developer`
- `DevOps-Cloud-AWS-Revision`
- `Site Reliability Engineer`
- `Cloud Engineer`
- `Azure DevOps`
- `Platform Engineer`
- `Security Engineer`
- `DevOps Engineer`
- `Automation Architect`

Goal:

```txt
Build strong fundamentals, revise interview questions, practice real-world scenarios,
and prepare project explanations for internships and fresher roles.
```

---

## How To Use This Repository

Daily method:

1. Open the relevant revision folder.
2. Read `Study.md` first.
3. Revise topic-wise files.
4. Practice `Interview-questions.md`.
5. Complete mini tasks.
6. Explain the topic out loud in 60 to 90 seconds.

Interview answer formula:

```txt
What it is -> Why it is used -> Real-world example -> Internal working -> Common mistakes -> Short conclusion
```

---

## Part 1: MERN Stack Revision

Folder:

```txt
MERN-Revision
```

Main topics:

- HTML
- CSS
- JavaScript
- React
- Next.js
- Node.js
- Express.js
- MongoDB
- Authentication
- System Design
- Projects
- DSA
- HR Round
- Mock Interview
- Rapid Revision
- Git, GitHub, and Deployment

Suggested MERN order:

1. JavaScript fundamentals and advanced JavaScript
2. React components, hooks, forms, routing, and state management
3. Node.js and Express.js APIs
4. MongoDB and schema design
5. Authentication with JWT, cookies, sessions, and roles
6. Next.js rendering and routing
7. Projects and system design
8. DSA and HR preparation
9. Mock interview and rapid revision

MERN daily practice:

```txt
60 min concepts
45 min coding
30 min interview questions
30 min project explanation
15 min HR practice
```

---

## Part 2: 7-Day DevOps + AWS Sprint

Folder:

```txt
DevOps-Cloud-AWS-Revision
```

This sprint converts a long DevOps roadmap into an interview-focused foundation plan.

---

## Day 1: Linux, Bash, Networking, Security

Goal:

```txt
Understand servers, shell, network basics, and secure access.
```

Topics:

- Linux file system hierarchy: `/etc`, `/var`, `/home`, `/tmp`
- Linux permissions: `chmod`, `chown`, users, groups
- Process management: `ps`, `top`, `kill`, `systemctl`
- Logs: `/var/log`, `tail -f`, `journalctl`
- Bash variables, loops, conditionals, functions
- Exit codes and cron jobs
- OSI and TCP/IP models
- DNS, IP addressing, subnetting
- SSH
- Firewalls, UFW, iptables
- AWS security groups basics

Mini tasks:

- Explain `chmod 755`.
- Write a Bash script to check disk usage.
- Explain what happens when you open a website.
- Design firewall rules for a web server.

---

## Day 2: Git, GitHub, Python For DevOps

Goal:

```txt
Version everything and automate repeated tasks.
```

Topics:

- Git working directory, staging area, commits
- Branching and merging
- Merge conflicts
- Git Flow vs GitHub Flow
- Pull requests
- GitHub webhooks
- Python `os`, `sys`, and `subprocess`
- Python automation scripts
- Virtual environments

Mini tasks:

- Create and resolve a merge conflict.
- Explain GitHub Flow.
- Write Python script to check if a URL is reachable.

---

## Day 3: AWS Cloud Fundamentals

Goal:

```txt
Move from local machine thinking to cloud infrastructure thinking.
```

AWS services:

- IAM users, groups, roles, and policies
- MFA and least privilege
- EC2 instances, AMI, key pairs, EBS
- S3 buckets, objects, permissions, storage classes
- VPC, CIDR, subnets, route tables
- Internet Gateway and NAT Gateway
- Security Groups vs NACL
- Lambda
- CloudWatch logs, metrics, alarms
- EventBridge basics

Mini tasks:

- Explain IAM user vs role.
- Explain EC2 vs Lambda.
- Design a VPC with public web server and private database.
- Explain how CloudWatch helps debugging.

---

## Day 4: Docker And Nginx

Goal:

```txt
Package applications consistently and manage traffic.
```

Topics:

- Docker images and containers
- Dockerfile instructions
- `.dockerignore`
- Volumes and bind mounts
- Container networking
- Docker Compose
- Nginx reverse proxy
- Nginx load balancing
- Static file serving
- SSL/TLS basics

Mini tasks:

- Dockerize a Node.js app.
- Explain image vs container.
- Configure Nginx as reverse proxy for Node.js.
- Explain volume vs bind mount.

---

## Day 5: CI/CD With Jenkins And Artifact Management

Goal:

```txt
Stop deploying manually.
```

Topics:

- CI/CD concepts
- Jenkins pipeline
- `Jenkinsfile`
- Declarative pipeline syntax
- Jenkins agents
- Jenkins credentials
- Git webhooks
- Docker Hub
- AWS ECR
- Image tagging
- Build artifacts and release flow

Mini tasks:

- Draw pipeline: Git push -> Jenkins -> Docker build -> registry -> deploy.
- Explain Jenkinsfile stages.
- Explain why secrets should not be hardcoded.
- Explain Docker Hub vs AWS ECR.

---

## Day 6: Kubernetes

Goal:

```txt
Manage containers at scale.
```

Topics:

- Kubernetes architecture
- Control plane and worker nodes
- Pods
- Deployments
- Replica management
- Services: ClusterIP, NodePort, LoadBalancer
- Ingress
- ConfigMaps
- Secrets
- Persistent Volumes and PVC
- `kubectl` debugging commands

Mini tasks:

- Explain pod vs container.
- Explain deployment vs service.
- Explain ConfigMap vs Secret.
- Debug a failing pod using `kubectl logs` and `kubectl describe`.

---

## Day 7: Terraform, Ansible, Prometheus, Grafana

Goal:

```txt
Create infrastructure using code and monitor systems.
```

Topics:

- Infrastructure as Code
- Terraform providers, resources, variables, outputs
- Terraform state
- `terraform plan`, `apply`, `destroy`
- AWS provisioning using Terraform
- Ansible inventory
- Ansible playbooks
- Ansible modules, variables, roles
- Idempotency
- Prometheus metrics and scraping
- Exporters
- Alerting
- Grafana dashboards

Mini tasks:

- Explain Terraform state.
- Terraform vs Ansible.
- Write steps for Ansible playbook to install Nginx.
- Design a Grafana dashboard for a Node.js API.

---

## DevOps Project Practice

Prepare these projects:

1. Deploy MERN app on AWS EC2 with Nginx.
2. Dockerize a Node.js backend.
3. Build Jenkins CI/CD pipeline.
4. Push Docker image to Docker Hub or AWS ECR.
5. Deploy app on Kubernetes.
6. Provision AWS resources using Terraform.
7. Configure server using Ansible.
8. Monitor app using Prometheus and Grafana.

Project explanation format:

```txt
Problem -> Architecture -> Tools used -> Deployment flow -> Security -> Monitoring -> Challenge -> Improvement
```

---

## Top DevOps Interview Questions

1. What is DevOps?
2. What is CI/CD?
3. What is Linux permission?
4. What is DNS?
5. What is SSH?
6. What is IAM?
7. IAM user vs role?
8. EC2 vs Lambda?
9. What is S3?
10. What is VPC?
11. Public subnet vs private subnet?
12. Security Group vs NACL?
13. What is Docker?
14. Docker image vs container?
15. Volume vs bind mount?
16. What is Nginx reverse proxy?
17. What is Jenkinsfile?
18. What is Docker image registry?
19. What is Kubernetes?
20. Pod vs deployment?
21. Service vs Ingress?
22. ConfigMap vs Secret?
23. What is Terraform state?
24. Terraform vs Ansible?
25. Prometheus vs Grafana?

---

## Placement Focus

For fresher interviews, focus on:

- Clear fundamentals
- Commands you can actually explain
- One strong MERN project
- One strong deployment project
- Basic AWS architecture
- CI/CD flow
- Docker basics
- Honest project challenges
- HR communication

---

## Part 3: Site Reliability Engineer Revision

Folder:

```txt
Site Reliability Engineer
```

Main topics:

- SRE mindset, toil reduction, and reliability culture
- SLIs, SLOs, SLAs, and error budgets
- Linux, networking, and production troubleshooting
- Observability with metrics, logs, traces, dashboards, and alerts
- Incident management, on-call, runbooks, and postmortems
- Reliability patterns, disaster recovery, and safe changes
- Automation with Bash and Python
- Cloud and Kubernetes operations
- CI/CD release engineering
- Capacity planning, performance, security, and compliance

Suggested SRE order:

1. SRE mindset and SLOs
2. Linux and networking troubleshooting
3. Observability and alerting
4. Incident response and postmortems
5. Reliability engineering and disaster recovery
6. Automation and health checks
7. Kubernetes and cloud operations
8. Release engineering and capacity planning
9. SRE projects and mock interviews

---

## Part 4: Cloud Engineer Revision

Folder:

```txt
Cloud Engineer
```

Main topics:

- Cloud fundamentals, service models, regions, and shared responsibility
- Linux, networking, DNS, HTTP, TLS, and security basics
- AWS IAM, EC2, S3, VPC, CloudWatch, Lambda, and RDS
- Compute, storage, databases, and serverless services
- VPC design, public and private subnets, DNS, CDN, and load balancing
- Monitoring, logging, backups, patching, and cloud operations
- Infrastructure as Code, Terraform, CloudFormation, CI/CD, and scripting
- Docker, container registry, ECS, EKS, and Kubernetes basics
- High availability, disaster recovery, migration, and scaling
- Cost optimization, tagging, budgets, governance, and multi-cloud basics

Suggested Cloud Engineer order:

1. Cloud fundamentals
2. Linux, networking, and security
3. AWS IAM and core services
4. Compute, storage, and databases
5. VPC, DNS, CDN, and load balancing
6. Monitoring, logging, and operations
7. Terraform, CI/CD, and automation
8. Containers and Kubernetes
9. High availability, disaster recovery, and cost optimization
10. Projects and mock interviews

---

## Part 5: Azure DevOps Revision

Folder:

```txt
Azure DevOps
```

Main topics:

- Azure fundamentals, subscriptions, resource groups, identity, and RBAC
- Azure DevOps Repos, Boards, Pipelines, Artifacts, and Test Plans
- Git workflows, pull requests, branch policies, and code reviews
- YAML pipelines, triggers, variables, stages, jobs, tasks, and templates
- CI/CD releases, environments, approvals, gates, deployment safety, and rollback
- Agents, agent pools, self-hosted agents, and service connections
- Azure Artifacts, feeds, packages, and versioning
- Docker, Azure Container Registry, AKS, Kubernetes, and Helm
- Terraform, Bicep, ARM templates, and Infrastructure as Code
- Azure Monitor, Log Analytics, Key Vault, Azure Policy, and pipeline security

Suggested Azure DevOps order:

1. Azure and Azure DevOps fundamentals
2. Git, Azure Repos, and branch policies
3. Azure Boards and agile planning
4. YAML CI pipelines
5. CD releases, environments, approvals, and rollback
6. Agents, pools, service connections, and permissions
7. Artifacts, Docker, ACR, AKS, and Kubernetes
8. Terraform, Bicep, monitoring, security, and governance
9. Testing, quality gates, projects, and mock interviews

---

## Part 6: Platform Engineer Revision

Folder:

```txt
Platform Engineer
```

Main topics:

- Platform Engineering fundamentals, developer experience, and platform as a product
- Internal Developer Platform, golden paths, paved roads, and guardrails
- Linux, networking, cloud, IAM, RBAC, and troubleshooting basics
- Kubernetes container platform, multi-tenancy, ingress, storage, and cluster operations
- Infrastructure as Code, Terraform modules, Crossplane, provisioning, and automation safety
- CI/CD, reusable pipeline templates, GitOps, Argo CD, Flux, and release strategies
- Observability, platform SLOs, dashboards, alerts, runbooks, and incident operations
- Secrets management, policy as code, supply chain security, and compliance guardrails
- Service catalog, software templates, ownership metadata, scorecards, and TechDocs
- Platform APIs, developer portals, CLIs, request workflows, reliability, scalability, and cost

Suggested Platform Engineer order:

1. Platform Engineering fundamentals
2. Linux, networking, and cloud basics
3. Developer experience and Internal Developer Platform
4. Kubernetes and container platform
5. IaC, provisioning, and automation
6. CI/CD and GitOps
7. Observability, operations, and platform SLOs
8. Security, secrets, policy, and compliance
9. Service catalog, templates, self-service, and platform APIs
10. Reliability, scalability, cost, team topology, projects, and mock interviews

---

## Part 7: MERN Stack Developer Revision

Folder:

```txt
MERN Stack Developer
```

Main topics:

- HTML, CSS, accessibility, responsive design, and browser fundamentals
- JavaScript core, async programming, event loop, DOM, fetch, and output questions
- TypeScript basics for React and backend API types
- React components, props, state, hooks, forms, routing, and API integration
- Advanced React state, Context API, Redux Toolkit, React Query, and performance
- Next.js App Router, rendering strategies, server and client components, and deployment
- Node.js runtime, modules, npm, event loop, streams, environment variables, and errors
- Express.js REST APIs, middleware, controllers, validation, CORS, cookies, and error handling
- MongoDB, Mongoose, schema design, relationships, indexes, and aggregation
- Authentication, authorization, JWT, cookies, sessions, refresh tokens, and RBAC
- Testing, debugging, logging, linting, deployment, DevOps basics, and system design
- MERN projects, project explanation, mock interviews, HR, and rapid revision

Suggested MERN Stack Developer order:

1. HTML, CSS, and browser fundamentals
2. JavaScript core and async programming
3. TypeScript basics
4. React fundamentals
5. Advanced React state and performance
6. Next.js basics
7. Node.js and Express.js backend development
8. MongoDB, Mongoose, authentication, and authorization
9. Testing, deployment, system design, and performance
10. Projects, mock interviews, HR, and rapid revision

---

## Part 8: Security Engineer Revision

Folder:

```txt
Security Engineer
```

Main topics:

- Security fundamentals, CIA triad, threat modeling, risk, and defense in depth
- Network security, firewalls, segmentation, DNS, TLS, VPN, IDS, IPS, and WAF
- Linux and endpoint hardening, logging, patching, and secure access
- Cloud security, IAM, least privilege, private networking, storage security, and audit logs
- Web application security, OWASP Top 10, API security, auth security, and rate limiting
- DevSecOps, SAST, DAST, SCA, secret scanning, image scanning, and pipeline gates
- SOC basics, SIEM, alert triage, incident response, and threat hunting
- Vulnerability management, CVSS, remediation tracking, and risk acceptance
- Secrets management, cryptography, hashing, encryption, PKI, and certificates
- Kubernetes security, RBAC, network policies, admission controls, compliance, and GRC

Suggested Security Engineer order:

1. Security fundamentals
2. Network security
3. Linux and endpoint security
4. Cloud security and IAM
5. Web and API security
6. DevSecOps
7. SOC, detection, and incident response
8. Vulnerability management, secrets, and cryptography
9. Kubernetes security, compliance, and GRC
10. Projects, mock interviews, and rapid revision

---

## Part 9: DevOps Engineer Revision

Folder:

```txt
DevOps Engineer
```

Main topics:

- Linux, networking, security, troubleshooting, and production server basics
- Git, GitHub, branching, pull requests, release flow, and team collaboration
- Bash and Python scripting, cron jobs, health checks, and safe automation
- CI/CD pipelines, Jenkins, GitHub Actions, artifacts, secrets, and rollback
- Docker, Dockerfile, Compose, registries, image tagging, and container networking
- Kubernetes architecture, pods, deployments, services, ingress, Helm, and debugging
- Cloud fundamentals across AWS, Azure, and Google Cloud
- Terraform, Infrastructure as Code, state, modules, and provisioning workflows
- Ansible, configuration management, idempotency, and drift control
- Observability, Prometheus, Grafana, logs, alerts, SRE basics, incidents, and DevSecOps

Suggested DevOps Engineer order:

1. Linux, networking, and security
2. Git and collaboration
3. Bash and Python automation
4. CI/CD pipelines
5. Docker and containers
6. Kubernetes orchestration
7. Cloud platforms
8. Terraform and Ansible
9. Monitoring, incidents, and DevSecOps
10. Projects, mock interviews, and rapid revision

---

## Part 10: Automation Architect Revision

Folder:

```txt
Automation Architect
```

Main topics:

- Automation fundamentals, strategy, ROI, standards, governance, and lifecycle ownership
- Process discovery, workflow mapping, automation candidate selection, and requirements
- Python, PowerShell, Bash, reusable scripts, logging, retries, and error handling
- Workflow orchestration, scheduling, dependencies, approvals, and human-in-the-loop design
- API integration, webhooks, queues, event-driven automation, and integration patterns
- Infrastructure automation, Terraform, Ansible, Crossplane, provisioning, and drift control
- CI/CD release automation, environment promotion, quality gates, approvals, and rollback
- Cloud automation, serverless automation, Kubernetes automation, and platform self-service
- RPA, low-code automation, bot governance, testing automation, observability, and AIOps basics
- Security, audit trails, compliance, scalability, reliability, cost, and automation projects

Suggested Automation Architect order:

1. Automation fundamentals and strategy
2. Process discovery and assessment
3. Scripting and reusable automation
4. Workflow orchestration
5. API and event-driven integration
6. Infrastructure and CI/CD automation
7. Cloud, platform, RPA, and low-code automation
8. Testing, observability, and auto-remediation
9. Security, governance, reliability, scalability, and cost
10. Projects, mock interviews, and rapid revision

Final reminder:

```txt
Do not memorize only definitions.
Explain with examples, commands, project flow, and mistakes you learned from.
```
