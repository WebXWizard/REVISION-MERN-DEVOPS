# CORS

CORS browser security mechanism hai jo cross-origin requests control karta hai.

Why important:

- Frontend and backend different domains par ho sakte hain.

Express setup:

```js
app.use(cors({ origin: "http://localhost:3000", credentials: true }));
```

Common mistakes:

- Credentials true but frontend credentials missing.
- Production origin configure na karna.

Interview questions:

- What is CORS?
- How to fix CORS error?

Mini task:

- Configure CORS for frontend domain.

