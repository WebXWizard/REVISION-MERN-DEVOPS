# VPC

VPC is your private network in AWS.

Core parts:

- CIDR block
- Subnet
- Route table
- Internet gateway
- NAT gateway
- Security group
- Network ACL

Good architecture:

```txt
Public subnets for load balancers and private subnets for app servers and databases.
```

