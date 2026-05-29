# Triggers And Variables

Triggers decide when a pipeline runs.

Common triggers:

- Push to branch
- Pull request
- Scheduled run
- Manual run

Variables store reusable values.

Examples:

```yaml
variables:
  nodeVersion: '20.x'
  buildConfiguration: 'Release'
```

Secret variables should be stored securely, not hardcoded in YAML.

