# Kubernetes Debugging

Check these first:

- Pod status
- Restart count
- Events
- Logs
- Image pull errors
- Resource limits
- Probes
- Service selectors

Commands:

```bash
kubectl describe pod pod-name
kubectl logs pod-name
kubectl get events
kubectl rollout status deployment/app
kubectl rollout undo deployment/app
```

