# iptables and UFW

`iptables` is low-level Linux firewall. `ufw` is simpler frontend for firewall rules.

Commands:

```bash
sudo ufw allow 22
sudo ufw allow 80
sudo ufw enable
sudo ufw status
```

Common mistakes:

- Blocking SSH while connected remotely.

Mini task:

- Explain safe order to enable UFW.

