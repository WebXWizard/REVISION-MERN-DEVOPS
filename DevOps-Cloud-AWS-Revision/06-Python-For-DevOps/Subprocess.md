# subprocess

`subprocess` runs external commands from Python.

Use case:

- Run `docker`, `git`, `kubectl`, or shell commands from automation script.

Example:

```python
import subprocess
result = subprocess.run(["ls", "-la"], capture_output=True, text=True)
print(result.stdout)
```

Common mistakes:

- Using `shell=True` unnecessarily.

Mini task:

- Run `git status` using subprocess.

