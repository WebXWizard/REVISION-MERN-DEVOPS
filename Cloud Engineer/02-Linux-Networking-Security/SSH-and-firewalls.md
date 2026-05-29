# SSH And Firewalls

SSH is used to securely connect to Linux servers.

Good SSH practices:

- Use key pairs.
- Disable password login where possible.
- Restrict source IP.
- Avoid exposing SSH publicly when a bastion or SSM is available.
- Rotate keys when needed.

Firewall concepts:

- Allow only required ports.
- Use security groups or firewall rules.
- Keep databases private.
- Separate public and private subnets.

