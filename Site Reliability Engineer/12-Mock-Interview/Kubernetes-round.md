# Kubernetes Round

Practice questions:

1. Pod is in CrashLoopBackOff. What do you do?
2. Pod is pending. What do you check?
3. Service is not reachable. What do you check?
4. How do you rollback a deployment?
5. What are liveness and readiness probes?

Debug commands:

```bash
kubectl describe pod pod-name
kubectl logs pod-name
kubectl get events
kubectl get svc
kubectl rollout undo deployment/app
```

