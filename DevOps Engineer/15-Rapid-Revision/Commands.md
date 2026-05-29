# Commands

Linux:

```bash
top
df -h
free -h
systemctl status service
journalctl -u service
```

Docker:

```bash
docker build -t app .
docker run -p 3000:3000 app
docker logs container-id
```

Kubernetes:

```bash
kubectl get pods
kubectl describe pod pod-name
kubectl logs pod-name
kubectl rollout undo deployment/app
```

Terraform:

```bash
terraform init
terraform plan
terraform apply
```

