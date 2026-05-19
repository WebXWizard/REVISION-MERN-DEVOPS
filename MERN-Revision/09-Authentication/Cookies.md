# Auth Cookies

Cookies auth tokens/session id store karne ke liye use ho sakti hain.

Important flags:

- `httpOnly`
- `secure`
- `sameSite`

Why used:

- Browser automatically cookie request ke saath bhejta hai.
- httpOnly cookie JS se inaccessible hoti hai.

Common mistakes:

- CORS credentials configure na karna.

Interview questions:

- Why httpOnly cookie?
- Cookies vs localStorage for JWT?

Mini task:

- Explain secure cookie setup for production.

