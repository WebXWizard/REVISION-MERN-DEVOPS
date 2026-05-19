# Promises

Promise async operation ka future result represent karta hai.

States:

- pending
- fulfilled
- rejected

Why used:

- Async code ko cleaner banana.

Example:

```js
fetch("/api/users")
  .then((res) => res.json())
  .then((data) => console.log(data))
  .catch((err) => console.error(err));
```

Common mistakes:

- `return` missing in promise chain.
- Errors catch na karna.

Mini task:

- Create promise that resolves after 1 second.

