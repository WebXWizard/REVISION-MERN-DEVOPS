# useMemo

`useMemo` expensive calculation ka result memoize karta hai.

Why used:

- Re-render par unnecessary recalculation avoid karne ke liye.

Example:

```jsx
const total = useMemo(() => calculateTotal(items), [items]);
```

Common mistakes:

- Har small calculation ke liye use karna.
- Dependencies galat dena.

Interview questions:

- What is useMemo?
- useMemo vs useCallback?

Mini task:

- Memoize filtered product list.

