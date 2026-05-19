# Authentication

Authentication verify karta hai user kaun hai.

Express flow:

```txt
Login request -> validate credentials -> generate token/session -> send response/cookie
```

Why used:

- Protected APIs ke liye.

Common mistakes:

- Plain password compare karna.
- Token verification middleware missing.

Interview questions:

- How authentication works in Express?
- Where do you verify JWT?

Mini task:

- Create login route and auth middleware.

