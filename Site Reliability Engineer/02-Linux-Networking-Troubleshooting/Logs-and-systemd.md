# Logs And systemd

Important commands:

```bash
systemctl status service-name
systemctl restart service-name
journalctl -u service-name
journalctl -u service-name --since "1 hour ago"
tail -f /var/log/nginx/error.log
```

What logs can show:

- Startup errors
- Permission issues
- Missing environment variables
- Port conflicts
- Database connection errors
- Upstream timeout errors

Good habit:

```txt
Always compare failure time with recent deployments, configuration changes, and traffic spikes.
```

