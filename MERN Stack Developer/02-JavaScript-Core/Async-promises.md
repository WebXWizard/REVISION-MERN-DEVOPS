# Async Programming And Promises

Promise states:

- Pending
- Fulfilled
- Rejected

Use `async` and `await` for readable asynchronous code.

Example:

```js
async function loadUser() {
  const res = await fetch("/api/user");
  return res.json();
}
```

Always handle errors with `try/catch` or `.catch()`.

