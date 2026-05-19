# JavaScript Study Notes

JavaScript is the core language of MERN. It runs in browser and Node.js.

Fundamentals:

- Variables: `var`, `let`, `const`
- Data types: primitive and non-primitive
- Functions: declaration, expression, arrow function
- Arrays and objects
- Operators and conditionals
- Loops

Advanced topics:

- Execution context
- Call stack
- Scope
- Hoisting
- Temporal Dead Zone
- Closures
- `this` keyword
- Prototype
- Event loop
- Callback, Promise, async/await
- Debouncing and throttling
- `map`, `filter`, `reduce`
- `call`, `apply`, `bind`

What happens when JS runs:

```txt
1. Global Execution Context is created.
2. Memory creation phase runs.
3. Code execution phase runs.
4. Function calls create new execution contexts.
5. Call stack manages execution order.
```

Real-world example:

- Form validation uses variables, functions, objects, arrays, and events.
- API calls use promises and async/await.
- Search input uses debouncing.

Common mistakes:

- Using `var` without understanding function scope.
- Comparing objects directly.
- Forgetting `return` in `map`.
- Mixing async code with sync expectations.
- Using arrow functions where dynamic `this` is needed.

Mini task:

- Write a debounced search function.
- Solve 5 output questions on hoisting and closures.

