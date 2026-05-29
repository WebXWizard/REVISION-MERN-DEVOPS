# Resilience Patterns

Common patterns:

- Timeout: stop waiting forever.
- Retry: try again for temporary failures.
- Backoff: wait longer between retries.
- Circuit breaker: stop calling a failing dependency.
- Bulkhead: isolate failures.
- Graceful degradation: serve limited functionality.
- Rate limiting: protect systems from overload.

Common mistake:

```txt
Unlimited retries can make an outage worse by increasing load.
```

