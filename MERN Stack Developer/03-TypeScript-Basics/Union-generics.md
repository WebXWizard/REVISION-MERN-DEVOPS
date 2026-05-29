# Union Types And Generics

Union type:

```ts
type Status = "pending" | "success" | "error";
```

Generic example:

```ts
function identity<T>(value: T): T {
  return value;
}
```

Generics help create reusable typed functions and components.

