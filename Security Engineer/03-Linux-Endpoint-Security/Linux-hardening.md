# Linux Hardening

Hardening steps:

- Disable unused services.
- Patch packages.
- Use SSH keys.
- Restrict sudo access.
- Configure firewall.
- Review open ports.
- Set correct file permissions.
- Enable audit and logs.

Useful commands:

```bash
ss -tulpn
systemctl status ssh
sudo ufw status
last
journalctl -xe
```

