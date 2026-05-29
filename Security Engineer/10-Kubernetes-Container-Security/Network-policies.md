# Network Policies

Network policies control pod-to-pod and pod-to-external traffic.

Use for:

- Restrict database access.
- Limit namespace traffic.
- Block unnecessary egress.
- Reduce lateral movement.

Good default:

```txt
Deny all, then allow required traffic.
```

