# Firewalls And Segmentation

Firewalls control allowed traffic.

Segmentation limits blast radius.

Common rules:

- Allow HTTPS to public app.
- Allow SSH only from trusted IP or bastion.
- Keep database private.
- Allow app to database on required port only.

Good habit:

```txt
Default deny, then allow only required traffic.
```

