# CI/CD For Cloud

CI/CD automates build, test, and deployment.

Cloud deployment flow:

```txt
Git push -> CI tests -> build artifact -> security scan -> deploy -> verify -> monitor
```

Tools:

- GitHub Actions
- Jenkins
- GitLab CI
- AWS CodePipeline
- AWS CodeBuild
- Argo CD

Good pipeline:

- Uses secrets safely.
- Has rollback.
- Publishes deployment status.
- Runs tests before deployment.

