# CORS And Cookies

CORS controls which origins can call your API from browsers.

Cookies can store session or JWT securely when configured correctly.

Cookie security options:

- `httpOnly`
- `secure`
- `sameSite`

Production habit:

```txt
Configure CORS with exact frontend domain, not wildcard, when credentials are used.
```

