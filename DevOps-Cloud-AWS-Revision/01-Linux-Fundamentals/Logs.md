# Logs

Logs help debug production issues.

Common locations:

- `/var/log/syslog`
- `/var/log/auth.log`
- `/var/log/nginx/access.log`
- `/var/log/nginx/error.log`

Commands:

```bash
tail -f app.log
journalctl -u nginx
grep "ERROR" app.log
```

Common mistakes:

- Looking only at frontend error.
- Not checking system/service logs.

Mini task:

- Use `tail -f` on any log file.

