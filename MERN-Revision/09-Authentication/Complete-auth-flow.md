# Complete Auth Flow

Full auth flow:

```txt
Register -> hash password -> save user
Login -> compare password -> create tokens
Access API -> verify access token
Expired access token -> refresh token endpoint
Logout -> clear cookie/token
Role route -> verify token + role
```

Interview focus:

- Auth vs authorization
- Access vs refresh token
- Cookie flags
- Backend role check

Common mistakes:

- Logout only frontend state clear karna.
- Refresh token security ignore karna.

Mini task:

- Draw complete MERN auth architecture.

