# System Design Study Notes

For freshers, system design means explaining architecture, APIs, database models, and basic scaling ideas clearly.

How to design any app:

```txt
1. Requirements
2. Main entities
3. APIs
4. Database schema
5. Auth and permissions
6. Basic architecture
7. Scaling points
8. Edge cases
```

Important designs:

- URL shortener
- Chat app
- Library management system
- E-commerce backend

URL shortener basics:

- User submits long URL.
- Server generates short code.
- DB stores code and original URL.
- Redirect API finds original URL and redirects.

Chat app basics:

- Users, conversations, messages.
- REST for history.
- WebSocket/Socket.IO for real-time messages.

Common mistakes:

- Starting with database before requirements.
- Ignoring edge cases.
- Not explaining tradeoffs.
- Overengineering fresher-level design.

Mini task:

- Design APIs and MongoDB schema for URL shortener.

