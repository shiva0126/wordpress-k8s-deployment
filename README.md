# wordpress-k8s-deployment

# WordPress Kubernetes Deployment

This repository contains the Kubernetes YAML files for deploying a WordPress application along with a MySQL database on a Kubernetes cluster.

## Files

- `mysql-deployment.yaml`: YAML file to deploy MySQL and expose it as a service.
- `wordpress-deployment.yaml`: YAML file to deploy WordPress and expose it as a service.

## How to Deploy

1. Clone the repository.
2. Apply the Kubernetes configurations:

```bash
kubectl apply -f wordpress/mysql-deployment.yaml
kubectl apply -f wordpress/wordpress-deployment.yaml
