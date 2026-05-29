# Performance Debugging

Debug slow systems by checking:

- Recent deployments
- p95 and p99 latency
- Database query time
- External dependency latency
- CPU and memory
- Lock contention
- Garbage collection
- Network latency

Useful approach:

```txt
Find where time is spent, then optimize the largest bottleneck first.
```

