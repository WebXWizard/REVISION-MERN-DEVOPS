# Request Lifecycle

Express request lifecycle:

```txt
Client -> server -> middleware -> route -> controller -> database -> response
```

Why important:

- Debugging and middleware order samajhne ke liye.

Common mistakes:

- Response send hone ke baad next middleware call karna.

Interview questions:

- Explain Express request lifecycle.
- Middleware order why important?

Mini task:

- Draw lifecycle for protected product creation API.

