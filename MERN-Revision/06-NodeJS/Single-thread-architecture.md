# Single Thread Architecture

Node.js JavaScript execution ke liye single-threaded model use karta hai, but async I/O background threads/libuv ke through handle hota hai.

Why useful:

- I/O-heavy apps efficiently handle karta hai.

Important:

- CPU-heavy work event loop block kar sakta hai.

Interview questions:

- Is Node.js single-threaded?
- How does Node handle multiple users?

Mini task:

- Explain single thread using restaurant waiter example.

