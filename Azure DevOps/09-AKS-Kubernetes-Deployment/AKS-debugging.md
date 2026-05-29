# AKS Debugging

Useful commands:

```bash
kubectl get pods
kubectl describe pod pod-name
kubectl logs pod-name
kubectl get events
kubectl get svc
kubectl get ingress
kubectl rollout undo deployment/app
```

Check:

- Image pull errors
- Pod restarts
- Readiness failures
- Service selectors
- Ingress rules
- Secret or ConfigMap names
- Resource limits

