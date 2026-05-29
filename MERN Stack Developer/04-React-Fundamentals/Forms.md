# React Forms

Controlled input:

- Value is controlled by React state.

Example:

```jsx
const [email, setEmail] = useState("");

<input value={email} onChange={(e) => setEmail(e.target.value)} />
```

Good forms handle:

- Input state
- Validation
- Loading
- Error messages
- Success state

