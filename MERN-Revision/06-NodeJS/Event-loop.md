# Node.js Event Loop

Node.js event loop async operations manage karta hai.

Why used:

- Non-blocking I/O handle karne ke liye.

Phases include:

- timers
- pending callbacks
- poll
- check
- close callbacks

Common mistakes:

- CPU-heavy task event loop block kar sakta hai.

Interview questions:

- Explain Node.js event loop.
- How Node handles multiple users?

Mini task:

- Predict output with `setTimeout`, `setImmediate`, and promise.

