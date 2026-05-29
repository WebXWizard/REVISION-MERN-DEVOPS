# Commands

Linux:

```bash
ss -tulpn
last
journalctl -u ssh
sudo ufw status
ps aux
```

Network:

```bash
curl -I https://example.com
dig example.com
nmap -sV target
openssl s_client -connect example.com:443
```

Kubernetes:

```bash
kubectl auth can-i get pods
kubectl get networkpolicy
kubectl get rolebinding -A
kubectl describe pod pod-name
```

