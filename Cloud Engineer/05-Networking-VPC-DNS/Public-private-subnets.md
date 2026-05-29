# Public And Private Subnets

Public subnet:

- Has route to internet gateway.
- Used for load balancers, bastion hosts, or NAT gateways.

Private subnet:

- No direct inbound internet access.
- Used for app servers, workers, and databases.

Security rule:

```txt
Databases should usually stay in private subnets.
```

