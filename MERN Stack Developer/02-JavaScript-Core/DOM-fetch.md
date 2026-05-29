# DOM And Fetch

DOM lets JavaScript interact with HTML.

Common DOM methods:

- `querySelector`
- `addEventListener`
- `classList`
- `createElement`

Fetch is used for HTTP requests.

Example:

```js
const res = await fetch("/api/products");
const data = await res.json();
```

Always handle loading, error, and empty states in UI.

