# Auth Flow

Typical auth flow:

```txt
Register -> Hash password -> Store user -> Login -> Verify password -> Create token/session -> Access protected route -> Logout
```

Important:

- Never store plain passwords.
- Validate input.
- Use secure cookies if storing tokens in cookies.
- Protect private routes with middleware.

