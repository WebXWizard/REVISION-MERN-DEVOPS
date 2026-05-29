# Commands

Git:

```bash
git status
git checkout -b feature/name
git add .
git commit -m "message"
git push origin feature/name
```

Azure CLI:

```bash
az login
az account show
az group list
az acr list
az aks get-credentials --resource-group rg-name --name aks-name
```

Docker:

```bash
docker build -t app .
docker run -p 3000:3000 app
docker push registry.azurecr.io/app:tag
```

Kubernetes:

```bash
kubectl get pods
kubectl describe pod pod-name
kubectl logs pod-name
kubectl rollout status deployment/app
```

Terraform:

```bash
terraform init
terraform plan
terraform apply
```

