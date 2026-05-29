# IAM And Least Privilege

Least privilege means users and services get only the permissions they need.

Good practices:

- Use roles instead of long-term keys.
- Enable MFA for humans.
- Avoid wildcard permissions.
- Rotate credentials.
- Review access regularly.
- Separate production and development access.

SRE concern:

```txt
Access should be secure but also available during incidents.
```

