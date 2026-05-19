# Error Handling

Express me centralized error handling app ko clean and predictable banata hai.

Error middleware signature:

```js
function errorHandler(err, req, res, next) {}
```

Why used:

- Consistent error response.
- Debugging easy.

Common mistakes:

- Async errors catch na karna.
- Stack trace production me expose karna.

Interview questions:

- How do you handle errors in Express?
- What is centralized error middleware?

Mini task:

- Add error handler to CRUD API.

