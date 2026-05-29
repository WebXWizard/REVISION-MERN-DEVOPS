# Deployments, Services, And Ingress

Deployment:

- Manages replicas and rollout.
- Keeps desired pod count running.

Service:

- Gives stable networking to pods.
- Types include ClusterIP, NodePort, and LoadBalancer.

Ingress:

- Routes external HTTP or HTTPS traffic to services.
- Often uses an ingress controller like Nginx.

Interview line:

```txt
Deployment manages pods, Service exposes pods internally or externally, and Ingress routes HTTP traffic by host or path.
```

