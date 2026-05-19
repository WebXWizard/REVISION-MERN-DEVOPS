# State

State component ka internal data hota hai jo change hone par UI re-render karta hai.

Why used:

- User interaction and dynamic UI ke liye.

Example:

```jsx
const [count, setCount] = useState(0);
```

Common mistakes:

- State directly mutate karna.
- State update ke turant baad updated value expect karna.

Interview questions:

- What is state?
- Why state update is asynchronous?

Mini task:

- Build counter with increment, decrement, reset.

