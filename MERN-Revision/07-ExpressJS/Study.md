# Express.js Study Notes

Express.js is a minimal Node.js framework used to build APIs and web servers.

Important topics:

- Routing
- Middleware
- Request and response objects
- Controllers
- Error handling
- REST API design
- Authentication
- Authorization
- JWT
- Cookies
- CORS
- Validation

Request lifecycle:

```txt
Client request -> Express app -> middleware chain -> route handler -> controller/service -> database -> response
```

Middleware:

- Function that runs between request and response.
- Used for logging, auth, validation, parsing JSON, error handling.

Common mistakes:

- Not calling `next()` in middleware.
- Sending multiple responses.
- Not using centralized error handling.
- Not validating request body.
- Putting all logic inside routes.

Mini task:

- Build REST APIs for products: create, read, update, delete, with validation and error handling.

