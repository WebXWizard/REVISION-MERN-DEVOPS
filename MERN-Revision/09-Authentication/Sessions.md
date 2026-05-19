# Sessions

Session server-side authentication state hota hai.

Flow:

```txt
Login -> server creates session -> session id cookie -> future requests use session id
```

Why used:

- Server can invalidate sessions easily.

Common mistakes:

- Session storage memory me rakhna in production without store.

Interview questions:

- What is session?
- Session vs JWT?

Mini task:

- Draw session-based login flow.

