# Cookies vs Sessions

Cookie browser side data store karta hai. Session usually server side user state store karta hai.

Difference:

```txt
Cookie: stored in browser
Session: stored on server
Cookie: sent with requests
Session: identified using session id cookie
```

Real-world example:

- Server creates session and sends session id in cookie.

Common mistakes:

- Cookie and session ko same samajhna.
- Session id ko insecure cookie me store karna.

Interview questions:

- Cookies vs sessions?
- Which is more secure?
- How does session login work?

Mini task:

- Draw session-based auth flow.

