# React Types

Props type:

```tsx
type ButtonProps = {
  label: string;
  onClick: () => void;
};

function Button({ label, onClick }: ButtonProps) {
  return <button onClick={onClick}>{label}</button>;
}
```

Common React types:

- Props
- State
- Event handlers
- Children
- API data

