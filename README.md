# Django on AKS with DataDog Monitoring

## Project Structure

This project deploys a Django application to Azure Kubernetes Service with DataDog monitoring.

## Deployment Steps

1. Terraform setup
2. Build and push Docker image
3. Kubernetes deployment
4. DataDog monitoring setup

## Requirements

- Azure CLI
- Terraform
- kubectl
- Helm
- Docker


##Helm
###Install DataDog using Helm
First, add the DataDog Helm repo:

bash
helm repo add datadog https://helm.datadoghq.com
helm repo update

