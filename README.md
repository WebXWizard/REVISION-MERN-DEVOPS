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
- `DevOps-Cloud-AWS-Revision`

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

Final reminder:

```txt
Do not memorize only definitions.
Explain with examples, commands, project flow, and mistakes you learned from.
```
