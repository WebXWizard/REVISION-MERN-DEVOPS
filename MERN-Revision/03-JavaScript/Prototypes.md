# Prototypes

Prototype JavaScript ka inheritance mechanism hai.

Why used:

- Objects methods share kar sakte hain without duplicate memory.

Example:

```js
function User(name) {
  this.name = name;
}

User.prototype.sayHi = function () {
  return `Hi ${this.name}`;
};
```

Internal working:

- Object property na mile to JS prototype chain me search karta hai.

Interview questions:

- What is prototype?
- What is prototype chain?

Mini task:

- Add a method to constructor prototype.

