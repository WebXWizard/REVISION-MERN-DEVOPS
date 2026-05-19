# Cookies

Cookies small key-value data hota hai jo browser store karta hai and requests ke saath server ko bhej sakta hai.

Why used:

- Sessions, authentication, tracking preferences.

Important flags:

- `httpOnly`
- `secure`
- `sameSite`
- `maxAge`

Real-world example:

- Login ke baad server httpOnly cookie set karta hai.

Common mistakes:

- Sensitive cookie without `httpOnly`.
- Production me `secure` flag miss karna.

Interview questions:

- What are cookies?
- Cookies vs localStorage?
- What is httpOnly cookie?

Mini task:

- Explain cookie-based login flow in 5 steps.

