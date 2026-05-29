# YAML Pipeline Basics

Basic structure:

```yaml
trigger:
- main

pool:
  vmImage: ubuntu-latest

steps:
- script: echo "Hello Azure Pipelines"
```

Common sections:

- `trigger`
- `pool`
- `variables`
- `stages`
- `jobs`
- `steps`
- `tasks`

