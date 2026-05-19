# Closures

Closure means inner function outer function ke variables ko remember karta hai.

Why used:

- Data privacy
- Function factories
- Maintaining state

Example:

```js
function counter() {
  let count = 0;
  return function () {
    count++;
    return count;
  };
}
```

Internal working:

- Function apne lexical environment ka reference keep karta hai.

Common mistakes:

- Loops with `var` and async callbacks.

Interview questions:

- What is closure?
- Real-world use of closure?

Mini task:

- Create private counter using closure.

