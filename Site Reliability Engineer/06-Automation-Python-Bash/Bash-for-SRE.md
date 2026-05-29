# Bash For SRE

Useful patterns:

```bash
set -euo pipefail
if systemctl is-active --quiet nginx; then
  echo "nginx is running"
fi
df -h
tail -n 100 /var/log/syslog
```

Good Bash scripts:

- Validate input.
- Log important actions.
- Fail clearly.
- Avoid hardcoded secrets.
- Have dry-run mode for risky actions.

