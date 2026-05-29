# API Types

Type API responses to avoid UI mistakes.

Example:

```ts
type Product = {
  _id: string;
  name: string;
  price: number;
  inStock: boolean;
};
```

Good practice:

- Type loading state.
- Type error state.
- Type response data.
- Avoid `any` when possible.

