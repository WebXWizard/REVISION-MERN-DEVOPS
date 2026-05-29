# Fault Tolerance

Fault tolerance means the system continues operating when a component fails.

Examples:

- Multi-AZ database
- Multiple app replicas
- Retry with backoff
- Queue-based processing
- Circuit breakers
- Graceful degradation

Common mistake:

```txt
Retries without limits can overload a failing dependency.
```

