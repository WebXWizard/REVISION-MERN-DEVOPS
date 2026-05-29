# Token Storage

Storage options:

- Memory
- httpOnly cookie
- localStorage
- sessionStorage

For sensitive tokens, httpOnly secure cookies are often safer than localStorage because JavaScript cannot read them.

Avoid putting secrets in frontend code.

