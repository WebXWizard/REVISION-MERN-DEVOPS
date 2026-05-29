# Secrets Management

Secrets include:

- API keys
- Database passwords
- Tokens
- Private keys
- Certificates

Good practices:

- Do not commit secrets.
- Use a secrets manager.
- Rotate secrets.
- Limit access.
- Audit secret reads.
- Use environment-specific secrets.

Incident step:

```txt
If a secret leaks, revoke it, rotate it, search usage, and review access logs.
```

