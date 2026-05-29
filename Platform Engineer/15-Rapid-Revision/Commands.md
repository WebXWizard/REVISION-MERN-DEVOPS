# Commands

Kubernetes:

```bash
kubectl get pods
kubectl describe pod pod-name
kubectl logs pod-name
kubectl get events
kubectl get ns
kubectl auth can-i get pods
```

Docker:

```bash
docker build -t app .
docker run -p 3000:3000 app
docker push registry/app:tag
```

Terraform:

```bash
terraform init
terraform plan
terraform apply
terraform output
```

Argo CD:

```bash
argocd app list
argocd app get app-name
argocd app sync app-name
argocd app rollback app-name
```

