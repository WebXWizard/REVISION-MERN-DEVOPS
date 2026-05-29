# Routing And Controllers

Route:

- Defines endpoint and HTTP method.

Controller:

- Handles request logic.

Example flow:

```txt
Request -> Route -> Middleware -> Controller -> Service/database -> Response
```

Good practice:

- Keep routes clean.
- Move business logic out of route files.
- Use clear folder structure.

