# VPC Design

Good VPC design includes:

- CIDR range
- Public subnets
- Private subnets
- Route tables
- Internet gateway
- NAT gateway
- Security groups
- NACLs

Common pattern:

```txt
Public subnet: load balancer and NAT gateway
Private subnet: app servers and databases
```

