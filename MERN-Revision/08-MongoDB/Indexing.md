# Indexing

Index query performance improve karta hai.

Why used:

- Fast search, filtering, sorting.

Example:

```js
db.users.createIndex({ email: 1 });
```

Common mistakes:

- Har field par index banana.
- Index write performance impact ignore karna.

Interview questions:

- What is index?
- Why indexes improve reads?

Mini task:

- Add unique index on email.

