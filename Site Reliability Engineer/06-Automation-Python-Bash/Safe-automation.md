# Safe Automation

Automation should not create bigger incidents.

Safety rules:

- Use dry-run mode.
- Add clear logs.
- Set limits.
- Add timeouts.
- Confirm target environment.
- Avoid deleting data automatically.
- Prefer reversible actions.
- Notify humans for risky actions.

Auto-remediation examples:

- Restart unhealthy pod.
- Clear old temporary files.
- Scale replicas during high load.
- Rotate expired non-critical token.

