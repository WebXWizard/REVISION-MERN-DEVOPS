# Authentication Study Notes

Authentication means verifying who the user is. Authorization means checking what the user is allowed to do.

Important topics:

- Password hashing
- JWT
- Access token
- Refresh token
- Cookies
- Sessions
- Role-based access control
- Protected routes
- Logout flow

JWT login flow:

```txt
1. User sends email/password.
2. Server validates credentials.
3. Server creates access token and refresh token.
4. Access token is used for protected APIs.
5. Refresh token is used to get new access token.
6. Logout clears token/cookie.
```

Cookie-based auth flow:

```txt
Browser -> login request -> server sets httpOnly cookie -> browser automatically sends cookie on future requests -> server verifies token/session
```

Common mistakes:

- Storing plain passwords.
- Storing sensitive token in unsafe place.
- Not setting cookie flags.
- No token expiry.
- No role check on backend.
- Only hiding frontend buttons and calling it authorization.

Mini task:

- Draw auth flow for login, protected route, refresh token, and logout.

