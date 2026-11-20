# DevOps & Cloud Projects

Welcome! This repository showcases my professional DevOps and cloud projects.  
Each project is presented with an overview, documentation, and a link to its dedicated repository.

---

## 1️⃣ Shoppy Cart — Production-Grade GitOps Platform on AWS EKS

**Description:** End-to-end DevOps platform deploying an 12-service microservices application on AWS EKS. Implements five enterprise pillars: Terraform infrastructure, GitHub Actions CI with Trivy and ECR, ArgoCD GitOps with automated image updates, Gateway API + ExternalDNS networking with ACM TLS, and full observability (Prometheus/Grafana/Alertmanager + ELK). Includes HPA autoscaling, rollback safety, and EKS Pod Identity for least-privilege access. Built across five working repos with clear ownership boundaries (infra, app, gitops, platform, observability) and documented end-to-end with 19 implementation phases, 15 real gotchas, and production-shaped runbooks.

**Documentation:** [shoppy-cart-doc](https://github.com/shoppy-cart-org/shoppy-cart-doc)

---

## 2️⃣ Falla237 Container Delivery CI Pipeline
**Description:**  Automated CI/CD pipeline for containerized applications with multi-registry delivery and security scanning. Implements event-triggered workflows for pull request validation, development builds, and versioned releases.  
**Repository:** [falla237-container-delivery](https://github.com/Fouda-Emmanuel/falla237-container-delivery.git)

---

## Java BuildFlow CI System

**Description:** Automated CI pipeline for Java applications with build, testing, and code quality analysis. Integrates Maven, SonarQube, Nexus, and Slack for continuous feedback and artifact management.   
**Repository:** [java-buildflow-ci-system](https://github.com/Fouda-Emmanuel/java-buildflow-ci-system.git)

---

## AWS ShipFlow CD System

**Description:** Continuous Delivery pipeline for containerized applications using Docker, Amazon ECR, and ECS. Implements automated deployment workflows with staging and production environments via AWS CLI.   
**Repository:** [aws-shipflow-cd-system](https://github.com/Fouda-Emmanuel/aws-shipflow-cd-system.git)

---

## Terraform AWS Multi-Tier State
**Description:** Complete multi-tier infrastructure provisioning on AWS using Terraform with a focus on centralized state management. Deploys VPC with public/private subnets across multiple AZs, bastion host, RDS, ElastiCache, Amazon MQ, and Elastic Beanstalk. Implements remote state storage with S3 and state locking with DynamoDB — not just automation, but professional infrastructure state management.  
**Repository:** [terraform-aws-multi-tier-state](https://github.com/Fouda-Emmanuel/terraform-aws-multi-tier-state.git)

---

## Terraform & Ansible – ALB VPC Architecture
**Description:** Builds a highly available AWS web architecture with VPC, multi-AZ setup, and ALB. EC2 instances configured with Ansible.  
**Repository:** *[terraform-ansible-alb-vpc](https://github.com/Fouda-Emmanuel/terraform-ansible-alb-vpc.git)*

---

## Lift & Shift – AWS Console
**Description:** Migration of the VProfile multi-tier app to AWS using Classic Load Balancer, Auto Scaling, EC2, RDS, Memcached, and RabbitMQ.  
**Repository:** [lift-and-shift-aws-console](https://github.com/Fouda-Emmanuel/lift-and-shift-aws-console.git)

---

## Terraform & Ansible – Multi-Instance Nginx
**Description:** Provisions two AWS EC2 instances running Nginx using Terraform and Ansible.  
**Repository:** *[terraform-ansible-multi-instance-nginx](https://github.com/Fouda-Emmanuel/terraform-ansible-multi-instance-nginx.git)*

---

## Terraform & Ansible – EC2 Nginx
**Description:** Provisions a single EC2 instance with Nginx using Terraform and Ansible, demonstrating IaC workflow.  
**Repository:** *[terraform-ansible-ec2-nginx](https://github.com/Fouda-Emmanuel/terraform-ansible-ec2-nginx.git)*

---

> All projects are organized in separate repositories for clarity and maintainability.
