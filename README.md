# Kubernetes Project

GitHub Actions workflows for deploying applications to Kubernetes using kubectl and Helm.

## Structure

- `k8s/` - Kubernetes manifests (Pod, Deployment, Service)
- `helm-chart/` - Helm chart for application deployment
- `.github/workflows/` - GitHub Actions workflows

## Workflows

- `k8s-pod.yml` - Deploy a single pod with random name
- `k8s-deploy.yml` - Full CI/CD with Docker build and Kubernetes deployment
- `helm-deploy.yml` - CI/CD using Helm charts

## Usage

1. Ensure self-hosted runner is configured
2. Update image repository names in workflows
3. Push to main branch or trigger workflow manually

