# Populate

Mongoose `populate` referenced documents ko fetch karne ke liye use hota hai.

Example:

```js
Order.find().populate("user");
```

Why used:

- Referenced data easily access karne ke liye.

Common mistakes:

- Overusing populate and making queries slow.

Interview questions:

- What is populate?
- Populate vs aggregation lookup?

Mini task:

- Create Order schema with user reference and populate it.

