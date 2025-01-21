# Install EKS

Please follow the prerequisites doc before this.

## Install using Fargate

```
eksctl create cluster --name demo-cluster-three-tier-1 --region us-east-1
eksctl create cluster --name demo-cluster-three-tier-1 --region eu-central-1
```

## Delete the cluster

```
eksctl delete cluster --name demo-cluster-three-tier-1 --region us-east-1
eksctl delete cluster --name demo-cluster-three-tier-1 --region eu-central-1
```
eksctl delete cluster --name Kubernetes-demo-jan2025 --region eu-central-1


