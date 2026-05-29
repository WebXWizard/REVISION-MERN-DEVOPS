# Error Budgets

An error budget is the allowed amount of unreliability.

Example:

```txt
If the SLO is 99.9 percent availability, the error budget is 0.1 percent downtime or failed requests.
```

Why it matters:

- It creates a data-based balance between speed and stability.
- If the budget is healthy, teams can release normally.
- If the budget is burned too fast, teams focus on reliability work.

Common causes of error budget burn:

- Bad deployments
- Infrastructure failures
- Dependency outages
- Traffic spikes
- Slow database queries

