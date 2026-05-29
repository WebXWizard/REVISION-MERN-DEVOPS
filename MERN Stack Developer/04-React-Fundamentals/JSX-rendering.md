# JSX And Rendering

JSX lets you write UI-like syntax in JavaScript.

Conditional rendering:

```jsx
{isLoggedIn ? <Dashboard /> : <Login />}
```

List rendering:

```jsx
{products.map((product) => (
  <ProductCard key={product._id} product={product} />
))}
```

Keys help React identify list items.

