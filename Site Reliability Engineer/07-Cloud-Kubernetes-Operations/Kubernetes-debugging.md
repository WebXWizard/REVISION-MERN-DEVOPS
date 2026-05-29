# Kubernetes Debugging

Useful commands:

```bash
kubectl get pods
kubectl describe pod pod-name
kubectl logs pod-name
kubectl logs pod-name --previous
kubectl get events --sort-by=.metadata.creationTimestamp
kubectl top pods
kubectl rollout status deployment/app
kubectl rollout undo deployment/app
```

Check:

- Pod status
- Restart count
- Events
- Image pull errors
- ConfigMap or Secret issues
- Resource limits
- Readiness probe failures

