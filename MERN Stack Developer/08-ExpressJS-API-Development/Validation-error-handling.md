# Validation And Error Handling

Validate:

- Request body
- Params
- Query
- File input

Common libraries:

- Zod
- Joi
- express-validator

Error middleware:

```js
app.use((err, req, res, next) => {
  res.status(err.status || 500).json({ message: err.message });
});
```

