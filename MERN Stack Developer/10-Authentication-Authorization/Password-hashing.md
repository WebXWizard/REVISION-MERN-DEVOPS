# Password Hashing

Passwords must be hashed before storage.

Common library:

- bcrypt

Hashing flow:

```txt
Plain password -> Salt -> Hash -> Store hash
```

Login flow:

```txt
User enters password -> Compare with stored hash -> Allow or reject
```

