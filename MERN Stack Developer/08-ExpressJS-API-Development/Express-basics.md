# Express Basics

Express creates HTTP servers and APIs.

Basic app:

```js
import express from "express";

const app = express();
app.use(express.json());

app.get("/health", (req, res) => {
  res.json({ status: "ok" });
});
```

Use Express for REST APIs, middleware, auth, and request handling.

