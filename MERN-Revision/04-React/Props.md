# Props

Props parent component se child component me data pass karte hain.

Why used:

- Reusable and configurable components banane ke liye.

Example:

```jsx
function Button({ label }) {
  return <button>{label}</button>;
}
```

Important:

- Props read-only hote hain.

Common mistakes:

- Child component me props mutate karna.

Interview questions:

- What are props?
- Props vs state?

Mini task:

- Create `UserCard` component using props.

