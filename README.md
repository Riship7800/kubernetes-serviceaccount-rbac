# Kubernetes Service Account – Automated kubectl Access

## Project Overview
This project demonstrates how to use Kubernetes Service Accounts with RBAC
to enable secure, automated kubectl access without using human user credentials.

This setup is commonly used in CI/CD pipelines and automation tools.

## Technologies Used
- Kubernetes (Minikube)
- kubectl
- RBAC (Role, RoleBinding)
- Service Accounts

## Steps Implemented
1. Created a Kubernetes ServiceAccount
2. Defined Role with limited pod read permissions
3. Bound Role to ServiceAccount using RoleBinding
4. Generated ServiceAccount token
5. Verified access using token-based kubectl authentication

## Commands Used

Create ServiceAccount:
```bash
kubectl create serviceaccount my-sa
