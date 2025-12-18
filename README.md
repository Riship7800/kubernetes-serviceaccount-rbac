# Kubernetes Service Account Based KUBECONFIG

## Description
This project demonstrates how to securely access the Kubernetes API
from external scripts using a ServiceAccount-based KUBECONFIG file.

## Features
- No user login required
- Least privilege RBAC
- Suitable for automation & CI/CD
- Secure external API access

## Steps Implemented
1. Namespace creation
2. Service Account setup
3. Role & RoleBinding
4. Token extraction
5. Custom KUBECONFIG creation
6. Access verification

## Tools Used
- Kubernetes
- kubectl
- RBAC
- YAML

## Use Case
Used for automation scripts, CI/CD pipelines, and external applications.
