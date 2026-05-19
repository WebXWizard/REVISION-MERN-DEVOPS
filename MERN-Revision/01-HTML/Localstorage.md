# LocalStorage

`localStorage` browser me key-value data permanently store karta hai until manually removed.

Why used:

- Theme preference, cart draft, non-sensitive UI settings.

Example:

```js
localStorage.setItem("theme", "dark");
localStorage.getItem("theme");
localStorage.removeItem("theme");
```

Common mistakes:

- JWT or sensitive user data store karna.
- Object directly store karna without `JSON.stringify`.

Interview questions:

- What is localStorage?
- Is localStorage secure for tokens?
- localStorage vs sessionStorage?

Mini task:

- Save dark mode preference in localStorage.

