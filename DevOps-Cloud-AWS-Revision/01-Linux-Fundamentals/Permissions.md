# Permissions

Linux permissions control who can read, write, and execute files.

Permission types:

- `r`: read
- `w`: write
- `x`: execute

User classes:

- owner
- group
- others

Commands:

```bash
chmod 755 script.sh
chown ubuntu:ubuntu app.log
```

Common mistakes:

- Using `chmod 777` everywhere.
- Wrong file owner for app directories.

Interview questions:

- What does `chmod 755` mean?
- `chmod` vs `chown`?

Mini task:

- Create a script and make it executable.

