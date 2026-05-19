# Event Loop

Event loop asynchronous code ko manage karta hai.

Parts:

- Call stack
- Web APIs / Node APIs
- Callback queue
- Microtask queue
- Event loop

Priority:

```txt
Call stack -> microtasks -> macrotasks
```

Common examples:

- `setTimeout`
- Promises
- DOM events
- API calls

Common mistakes:

- `setTimeout(..., 0)` ko immediate samajhna.

Mini task:

- Predict output of promise and setTimeout mixed code.

