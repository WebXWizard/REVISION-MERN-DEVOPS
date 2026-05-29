# SRE Answer Framework

Use this format for interview answers:

```txt
What failed -> User impact -> Detection signal -> Immediate action -> Root cause -> Prevention
```

Example:

```txt
The API latency increased. Users saw slow page loads. We detected it using p95 latency and error-rate alerts. First we rolled back the latest deployment and scaled replicas. Then we checked logs, traces, and recent changes. Root cause was an inefficient database query. Prevention was query optimization, load testing, and an SLO-based alert.
```

Good SRE answers should include:

- Business or user impact
- Metrics and evidence
- Practical debugging steps
- Short-term mitigation
- Long-term prevention
- Clear ownership and communication

