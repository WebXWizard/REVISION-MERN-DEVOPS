# CRUD Queries

CRUD means:

- Create
- Read
- Update
- Delete

Mongoose examples:

```js
await Product.create(data);
await Product.find();
await Product.findById(id);
await Product.findByIdAndUpdate(id, data);
await Product.findByIdAndDelete(id);
```

Always validate input before writing to database.

