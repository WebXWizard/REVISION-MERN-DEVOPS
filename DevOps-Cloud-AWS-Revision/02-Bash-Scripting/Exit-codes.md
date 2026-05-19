# Exit Codes

Exit code tells command success or failure.

Meaning:

- `0`: success
- non-zero: failure

Check:

```bash
echo $?
```

Why used:

- CI/CD pipelines decide pass/fail using exit codes.

Mini task:

- Run successful and failing commands and check `$?`.

