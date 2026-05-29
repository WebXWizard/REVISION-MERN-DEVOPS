# Queues And Background Jobs

Queues decouple slow work from user requests.

Use for:

- Sending emails
- Processing images
- Generating reports
- Payment webhooks
- Notifications

Flow:

```txt
API receives request -> Add job to queue -> Worker processes job -> Store result
```

