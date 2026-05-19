# JavaScript Interview Questions

Concept questions:

1. What is JavaScript?
2. Difference between `var`, `let`, and `const`.
3. What is hoisting?
4. What is Temporal Dead Zone?
5. What is scope?
6. What is closure?
7. Explain event loop.
8. Callback vs Promise vs async/await.
9. What is prototype?
10. Explain `this` keyword.
11. Difference between `==` and `===`.
12. What is debouncing?
13. What is throttling?
14. `map` vs `filter` vs `reduce`.
15. `call` vs `apply` vs `bind`.

Output questions:

```js
console.log(a);
var a = 10;
```

```js
console.log(typeof null);
console.log(typeof []);
```

```js
for (var i = 0; i < 3; i++) {
  setTimeout(() => console.log(i), 1000);
}
```

```js
let a = [1, 2];
let b = a;
b.push(3);
console.log(a);
```

Coding questions:

1. Write a function to remove duplicates from an array.
2. Write a function to count character frequency.
3. Implement debounce.
4. Implement throttle.
5. Flatten a nested array one level.
6. Write a promise chain with error handling.

Scenario questions:

1. Search API is called on every keypress. What will you do?
2. API calls should happen one after another. How will you handle?
3. A function remembers old data. Which concept is involved?
4. UI is blocked by heavy JS code. What can be the reason?

