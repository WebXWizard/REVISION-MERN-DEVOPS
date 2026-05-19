# MongoDB Study Notes

MongoDB is a NoSQL document database. It stores data in collections and documents.

Important topics:

- Database
- Collections
- Documents
- CRUD operations
- Schema design
- Mongoose basics
- Relationships
- Populate
- Indexing
- Aggregation pipeline
- Transactions basics

SQL vs MongoDB:

```txt
SQL: tables, rows, fixed schema, joins
MongoDB: collections, documents, flexible schema, embedding/references
```

Real-world example:

- User collection stores user profiles.
- Product collection stores product data.
- Order collection references user and products.

Internal working:

- Documents are stored in BSON format.
- Indexes improve read performance.
- Aggregation processes data through pipeline stages.

Common mistakes:

- Designing MongoDB exactly like SQL.
- Not creating indexes for frequent queries.
- Overusing populate.
- Storing huge arrays inside one document.
- Not validating schema in Mongoose.

Mini task:

- Design schemas for User, Product, Cart, and Order for an e-commerce app.

