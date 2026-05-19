# Lifecycle

React lifecycle component ke mount, update, and unmount phases ko describe karta hai.

Functional component mapping:

```txt
Mount: useEffect with []
Update: useEffect with dependencies
Unmount: cleanup function
```

Why used:

- API calls, subscriptions, cleanup.

Common mistakes:

- Cleanup missing for timers/listeners.

Interview questions:

- Explain React lifecycle.
- How useEffect replaces lifecycle methods?

Mini task:

- Add and cleanup window resize listener.

