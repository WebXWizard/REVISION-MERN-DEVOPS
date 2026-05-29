# DNS, TLS, And HTTP

DNS converts names to IP addresses.

TLS encrypts communication and verifies identity.

HTTP carries application requests and responses.

Common failures:

- DNS record points to old IP
- DNS TTL delays change
- TLS certificate expired
- HTTP 502 from upstream service
- HTTP 503 from unavailable service
- HTTP 504 from gateway timeout

Mini task:

- Explain what happens when a user opens `https://example.com`.

