# Azure DevOps Answer Framework

Use this format for interview answers:

```txt
Problem -> Repository workflow -> Pipeline stages -> Secrets and permissions -> Deployment environment -> Verification -> Rollback -> Improvement
```

Example:

```txt
For a Node.js app, I would keep code in Azure Repos, protect the main branch with PR policies, build using a YAML pipeline, run tests, publish artifacts, deploy to dev and prod environments with approvals, store secrets in Key Vault, monitor with Azure Monitor, and keep rollback ready using the previous release artifact.
```

Good answers include:

- Git workflow
- YAML pipeline structure
- Security and secret handling
- Artifact management
- Deployment strategy
- Monitoring and rollback
- Clear tradeoffs

