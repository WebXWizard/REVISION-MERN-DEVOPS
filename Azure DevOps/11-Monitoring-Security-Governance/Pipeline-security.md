# Pipeline Security

Pipeline security matters because pipelines can deploy code and infrastructure.

Good practices:

- Protect branches.
- Restrict service connections.
- Use approvals for production.
- Store secrets in Key Vault.
- Avoid printing secrets.
- Use least privilege.
- Review YAML changes.
- Scan dependencies and containers.

Important line:

```txt
Treat pipeline edit permission like production change permission.
```

