# Middleware

Middleware runs between request and response.

Use for:

- JSON parsing
- Authentication
- Logging
- Validation
- Error handling
- CORS

Example:

```js
app.use(express.json());
```

Middleware can end the response or call `next()`.

