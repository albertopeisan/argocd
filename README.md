# ArgoCD Setup

## Add ArgoCD Github Repository

Create a token and create repository in the ArgoCD settings.

## Create ArgoCD Project

```bash
kubectl apply -f ./projects/argocd.yaml
```

## Create ArgoCD Application

```bash
kubectl apply -f ./apps/argocd.yaml
```