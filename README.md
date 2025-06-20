# 🚀 Deploy a Dockerized Flask App using Ansible on Kubernetes (Minikube)

> ✅ Automate containerized app deployment on a local Kubernetes cluster using Ansible and Minikube

---

## 📌 Project Overview

This project demonstrates how to:

- Develop a simple **Flask** web app
- Containerize it using **Docker**
- Use **Ansible** to automate:
  - Docker image building inside **Minikube**
  - Deploying **Kubernetes manifests** (Deployment & Service)

Minikube is used as the local Kubernetes cluster, and all steps are managed inside a Linux shell (WSL2).

---

## ⚙️ Tech Stack

| Tool         | Purpose                         |
|--------------|----------------------------------|
| 🐍 Flask     | Python web framework             |
| 🐳 Docker    | Containerizing the Flask app     |
| ⚙️ Ansible   | Automate image build + K8s deploy |
| ☸️ Kubernetes| Orchestrate container deployment |
| 🧪 Minikube  | Local Kubernetes cluster         |
| 🐧 WSL2 + Ubuntu | Linux-based DevOps setup    |

---

## 📁 Project Structure

├── app/
│ ├── app.py
│ └── Dockerfile
├── k8s/
│ ├── deployment.yaml
│ └── service.yaml
├── deploy.yaml ← Ansible playbook


🌟 What I Learned
Real DevOps automation using Ansible

Working with Kubernetes YAML and Pods

Debugging tools like kubectl logs, describe

Image build inside Minikube context

Managing virtual environments in WSL2


📎 Useful Commands

# Get pods
kubectl get pods

# Describe service in detail
kubectl describe svc flask-service

# Check logs of the pod
kubectl logs <pod-name>
