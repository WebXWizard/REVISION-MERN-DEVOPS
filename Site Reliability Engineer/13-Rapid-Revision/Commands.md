# Commands

Linux:

```bash
top
free -h
df -h
ps aux
systemctl status service
journalctl -u service
```

Networking:

```bash
curl -I https://example.com
dig example.com
ss -tulpn
ip route
```

Kubernetes:

```bash
kubectl get pods
kubectl describe pod pod-name
kubectl logs pod-name
kubectl get events
kubectl rollout undo deployment/app
```

