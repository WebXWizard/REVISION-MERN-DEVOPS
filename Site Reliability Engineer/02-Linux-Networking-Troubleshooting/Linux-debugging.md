# Linux Debugging

Useful commands:

```bash
uptime
top
free -h
df -h
du -sh *
ps aux
systemctl status nginx
journalctl -u nginx -f
tail -f /var/log/syslog
```

What to check:

- High CPU usage
- Memory pressure
- Disk full
- Process crash loops
- Permission errors
- Service status
- Recent logs

Interview line:

```txt
I first check user impact, then system health, then service logs, then recent changes.
```

