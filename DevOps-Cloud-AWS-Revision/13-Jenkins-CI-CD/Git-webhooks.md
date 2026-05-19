# Git Webhooks

Webhook notifies Jenkins when code is pushed.

Flow:

```txt
Developer push -> GitHub webhook -> Jenkins job trigger -> pipeline runs
```

Common mistakes:

- Jenkins URL not reachable by GitHub.
- Webhook secret/config missing.

Mini task:

- Explain webhook-based CI flow.

