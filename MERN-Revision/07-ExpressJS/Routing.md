# Routing

Routing URL and HTTP method ke basis par handler execute karta hai.

Example:

```js
app.get("/users", getUsers);
app.post("/users", createUser);
```

Why used:

- REST APIs organize karne ke liye.

Common mistakes:

- Route order ignore karna.
- Controllers me separation na rakhna.

Interview questions:

- What is routing in Express?
- GET vs POST?

Mini task:

- Create CRUD routes for products.

