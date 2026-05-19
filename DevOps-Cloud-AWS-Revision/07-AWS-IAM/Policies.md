# IAM Policies

Policy is JSON document that defines permissions.

Contains:

- Effect
- Action
- Resource
- Condition

Example:

```json
{
  "Effect": "Allow",
  "Action": "s3:GetObject",
  "Resource": "*"
}
```

Mini task:

- Explain `Allow`, `Action`, and `Resource`.

