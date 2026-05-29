# Relationships And Populate

MongoDB can model relationships using:

- Embedding
- References

Embed when:

- Data is small and read together.

Reference when:

- Data is large or reused.

`populate` replaces referenced IDs with documents.

Example:

```js
Order.find().populate("user");
```

