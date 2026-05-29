# Mongoose Schemas

Mongoose schema defines document structure.

Example:

```js
const productSchema = new mongoose.Schema({
  name: { type: String, required: true },
  price: { type: Number, required: true },
  inStock: { type: Boolean, default: true }
});
```

Schemas help with validation, defaults, and model methods.

