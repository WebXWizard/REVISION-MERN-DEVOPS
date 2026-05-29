# GitOps

GitOps uses Git as the source of truth for desired system state.

Flow:

```txt
Change manifest in Git -> Review PR -> Merge -> GitOps controller applies change -> Monitor drift
```

Benefits:

- Audit trail
- Reviewable changes
- Easy rollback
- Drift detection
- Consistent deployments

