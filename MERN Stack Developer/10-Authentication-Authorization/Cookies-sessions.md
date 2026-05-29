# Cookies And Sessions

Cookie:

- Stored by browser.
- Sent with requests.

Session:

- Server-side auth state linked to session ID.

Secure cookie options:

- `httpOnly`
- `secure`
- `sameSite`

Auth decision:

```txt
httpOnly cookies reduce token theft risk from XSS compared to localStorage.
```

