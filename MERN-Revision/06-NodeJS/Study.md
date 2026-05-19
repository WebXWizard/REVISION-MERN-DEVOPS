# Node.js Study Notes

Node.js is a JavaScript runtime built on Chrome's V8 engine. It lets JavaScript run outside the browser.

Important topics:

- Runtime vs language
- Modules: CommonJS and ES Modules
- NPM
- `package.json`
- Event loop
- Non-blocking I/O
- File system
- Streams
- Buffer
- Process
- Environment variables
- Cluster basics

Why Node.js:

- Same language on frontend and backend
- Handles I/O-heavy apps efficiently
- Large NPM ecosystem
- Good for APIs, real-time apps, and microservices

Internal working:

```txt
Request comes -> JS call stack handles code -> async I/O delegated -> callback queue -> event loop pushes callback when stack is free
```

Common mistakes:

- Saying Node.js is multi-threaded like Java.
- Blocking event loop with heavy CPU tasks.
- Committing `.env` files.
- Not handling async errors.
- Installing packages without checking need.

Mini task:

- Create a small Node.js script that reads a file, processes text, and writes a summary.

