# Kubernetes Plain Manifests Copier Template

Copier template for Kubernetes deployments without Helm charts.

## Usage
```bash
copier copy gh:arookieds/k8s-plain-manifests-template /path/to/new-project
```

## Features

- Pure Kubernetes manifests
- Supports Deployment, StatefulSet, DaemonSet, Job
- Environment overlays
- ConfigMap and Sealed Secrets
- Service and Ingress configuration

## Requirements

- Python 3.10+
- Copier 9.0+
- kubectl
