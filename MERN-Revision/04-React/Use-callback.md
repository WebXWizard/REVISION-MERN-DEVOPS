# useCallback

`useCallback` function reference memoize karta hai.

Why used:

- Child component unnecessary re-render avoid karne me help karta hai.

Example:

```jsx
const handleClick = useCallback(() => {
  setCount((c) => c + 1);
}, []);
```

Common mistakes:

- Without memoized child, unnecessary use karna.
- Dependency array wrong rakhna.

Interview questions:

- What is useCallback?
- When should you use it?

Mini task:

- Use `React.memo` with `useCallback`.

