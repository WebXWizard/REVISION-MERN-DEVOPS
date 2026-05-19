# Middleware

Middleware request and response ke beech run hone wala function hai.

Signature:

```js
function middleware(req, res, next) {}
```

Use cases:

- Logging
- Auth
- Validation
- Error handling

Common mistakes:

- `next()` call na karna.
- Multiple response send karna.

Interview questions:

- What is middleware?
- Middleware execution order?

Mini task:

- Create logger middleware.

