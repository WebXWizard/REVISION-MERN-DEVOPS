# Kubernetes Deployments

Important objects:

- Deployment
- Service
- Ingress
- ConfigMap
- Secret
- Namespace

Pipeline deployment steps:

```txt
Build image -> Push to ACR -> Update manifest or Helm values -> Deploy to AKS -> Verify rollout
```

Verify:

```bash
kubectl rollout status deployment/app
kubectl get pods
kubectl logs pod-name
```

