# IaC Pipelines

IaC pipeline flow:

```txt
PR -> Validate -> Plan or what-if -> Approval -> Apply -> Verify
```

Good practices:

- Run validation on pull requests.
- Review Terraform plan or Bicep what-if.
- Use approvals for production.
- Keep secrets out of code.
- Store state securely.
- Separate environments.

