# Networking Debugging

Useful commands:

```bash
ping example.com
curl -I https://example.com
dig example.com
nslookup example.com
traceroute example.com
ss -tulpn
ip addr
ip route
```

Debug order:

1. Is DNS resolving?
2. Is the IP reachable?
3. Is the port open?
4. Is TLS valid?
5. Is the application returning a healthy response?
6. Is the load balancer routing correctly?

