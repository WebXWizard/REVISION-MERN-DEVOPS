# useEffect

`useEffect` side effects handle karta hai.

Use cases:

- API call
- Event listener
- Timer
- Subscription
- Document title update

Dependency array:

```txt
No array: every render
[]: only mount
[value]: when value changes
```

Common mistakes:

- Dependency missing.
- Infinite loop create karna.
- Cleanup function bhoolna.

Interview questions:

- Explain useEffect lifecycle.
- How to cleanup effect?

Mini task:

- Fetch users on component mount.

