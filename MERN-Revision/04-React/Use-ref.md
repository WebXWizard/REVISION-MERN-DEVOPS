# useRef

`useRef` mutable value store karta hai without re-render.

Use cases:

- DOM access
- Timer id
- Previous value
- Mutable reference

Example:

```jsx
const inputRef = useRef(null);
```

Common mistakes:

- UI data ke liye ref use karna instead of state.

Interview questions:

- What is useRef?
- useRef vs useState?

Mini task:

- Focus input using useRef.

