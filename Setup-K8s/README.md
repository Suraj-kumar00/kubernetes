## Ways to Create a Kubernetes Cluster

1. **Kubeadm** – A tool for bootstrapping a production-ready Kubernetes cluster by setting up control planes and nodes.
2. **Minikube** – A lightweight tool to run a single-node Kubernetes cluster locally or on a single EC2 instance for development and testing.
3. **Kind (Kubernetes in Docker)** – Runs Kubernetes clusters inside Docker containers, ideal for CI/CD and local testing.
4. **EKS/AKS/GKE (Managed Kubernetes Services)** – Fully managed Kubernetes offerings from AWS, Azure, and Google Cloud, handling cluster provisioning, scaling, and maintenance.

## Companies with Their Own Kubernetes Distributions

1. **Civo** – Cloud-native provider offering lightweight K3s-based Kubernetes clusters optimized for performance.
2. **Rancher** – Open-source Kubernetes management platform simplifying multi-cluster operations and security.
3. **Red Hat OpenShift** – Enterprise Kubernetes platform built on OpenShift/Kubernetes with built-in CI/CD, security, and developer tools.
4. **VMware Tanzu** – Kubernetes-based platform for managing cloud-native applications across multi-cloud environments.
5. **DigitalOcean Kubernetes (DOKS)** – A simple, developer-friendly managed Kubernetes service with built-in monitoring and scalability.
6. **Linode Kubernetes Engine (LKE)** – A cost-effective, managed Kubernetes service optimized for developers and startups.
7. **Mirantis Kubernetes Engine (MKE)** – Formerly Docker Enterprise, providing enterprise-grade Kubernetes with strong security and governance.
8. **Alibaba Cloud Container Service for Kubernetes (ACK)** – A managed Kubernetes service optimized for high-performance workloads in Alibaba Cloud.

---

## Kind Setup

## Minikube Setup

### How to start Minikube

Just use this command.

```bash
minikube start
```

### How to delete Minikube

Just use this command.

```bash
minikube delete
```

## How to Default context

```bash
kubectl config use-context <your-cluster-name>
```
