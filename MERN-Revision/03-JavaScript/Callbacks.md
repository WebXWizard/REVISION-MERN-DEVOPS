# Callbacks

Callback function ek function hota hai jo dusre function ko argument ke roop me pass hota hai.

Why used:

- Async operations
- Event handling
- Reusable logic

Example:

```js
setTimeout(() => {
  console.log("Done");
}, 1000);
```

Common mistakes:

- Callback hell create karna.
- Error-first callback pattern ignore karna in Node.js.

Interview questions:

- What is callback?
- What is callback hell?

Mini task:

- Convert nested callback example into promise.

