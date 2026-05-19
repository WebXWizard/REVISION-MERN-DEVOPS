# CORS in Production

CORS frontend and backend domains ke beech request control karta hai.

Production setup:

```js
app.use(cors({
  origin: process.env.CLIENT_URL,
  credentials: true
}));
```

Common mistakes:

- Localhost origin production me reh jana.
- Cookies ke liye credentials missing.

Interview questions:

- Why CORS error comes?
- How to configure CORS for production?

Mini task:

- Write CORS config for deployed frontend URL.

