# Role-Based Auth

Role-based auth user role ke basis par access allow/deny karta hai.

Roles:

- user
- admin
- manager

Flow:

```txt
Verify user -> check role -> allow or return 403
```

Common mistakes:

- Frontend-only role check.
- Role payload blindly trust karna without token verification.

Interview questions:

- What is RBAC?
- How to protect admin route?

Mini task:

- Create admin-only middleware.

