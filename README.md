# platform-project
This platform consists of:

platform-app → Helm chart repo
platform-gitops → GitOps environments
platform-terraform → infrastructure

Together they form a production delivery platform.
# Platform Delivery System

This project demonstrates a production-grade Kubernetes delivery platform built using modern platform engineering practices.

It includes GitOps automation, multi-environment deployments, Terraform infrastructure, observability, and security hardening.


---

## 📦 Helm Application Repo
🔗 https://github.com/respoamit/platform-app

---

## 🚀 GitOps Environment Repo
🔗 https://github.com/respoamit/platform-gitops

---

## 🏗 Terraform Infrastructure Repo
🔗 https://github.com/respoamit/platform-terraform

---

## Architecture Overview

Terraform → Cluster Infrastructure
GitOps Repo → Environment Control
Helm Chart → Application Packaging
ArgoCD → Continuous Deployment
Prometheus/Grafana → Monitoring
RBAC + Network Policies → Security

---

## Project Structure

platform-project/
├── app-chart/      # Helm application
├── gitops-repo/    # Dev/Staging/Prod environments
└── terraform/      # Infrastructure as Code

---

## Environments

dev → experimentation  
staging → testing  
prod → stable deployment

All environments are Git-driven and automatically deployed via ArgoCD.

---

## Features

- GitOps automated delivery
- Multi-environment platform design
- Terraform-managed infrastructure
- Observability stack included
- Kubernetes autoscaling
- Security hardening baseline
- Zero-trust namespace isolation

---

## How to Run

1. Apply Terraform
2. Install ArgoCD
3. Push GitOps repo
4. ArgoCD syncs environments automatically

---

## Skills Demonstrated

- Kubernetes platform architecture
- CI/CD + GitOps design
- Infrastructure as Code
- Observability engineering
- Security hardening
- Production deployment patterns


