# Async Await

`async/await` promises ko synchronous style me likhne ka syntax hai.

Why used:

- Async code readable banane ke liye.

Example:

```js
async function getUsers() {
  try {
    const res = await fetch("/api/users");
    const data = await res.json();
    return data;
  } catch (error) {
    console.error(error);
  }
}
```

Common mistakes:

- `await` ko non-async function me use karna.
- Error handling skip karna.

Mini task:

- Fetch API data using async/await and handle errors.

