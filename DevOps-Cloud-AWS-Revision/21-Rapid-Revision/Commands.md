# Commands

Linux:

```bash
ls -la
df -h
free -m
ps aux
tail -f app.log
systemctl status nginx
```

Docker:

```bash
docker build -t app .
docker run -p 3000:3000 app
docker ps
docker logs container-id
```

Kubernetes:

```bash
kubectl get pods
kubectl describe pod pod-name
kubectl logs pod-name
kubectl apply -f deployment.yaml
```

Terraform:

```bash
terraform init
terraform plan
terraform apply
terraform destroy
```

