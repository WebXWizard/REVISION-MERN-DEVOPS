# URL Shortener

Goal:

- Long URL ko short code me convert karna.

Main APIs:

- `POST /shorten`
- `GET /:code`

Schema:

```txt
code
originalUrl
clicks
createdAt
expiresAt
```

Scaling points:

- Unique code generation
- Index on code
- Rate limiting
- Analytics

Interview questions:

- How to handle duplicate code?
- How redirect works?

Mini task:

- Design DB schema and API flow.

