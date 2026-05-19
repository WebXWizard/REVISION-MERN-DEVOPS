# SessionStorage

`sessionStorage` tab/session close hone tak data store karta hai.

Why used:

- Temporary data, multi-step form draft, tab-specific state.

Example:

```js
sessionStorage.setItem("step", "2");
sessionStorage.getItem("step");
sessionStorage.clear();
```

Internal working:

- Data same browser tab ke session tak available rehta hai.

Common mistakes:

- Long-term data ke liye use karna.
- Sensitive data store karna.

Interview questions:

- sessionStorage kab clear hota hai?
- localStorage vs sessionStorage?

Mini task:

- Store current form step in sessionStorage.

