# API Integration

Frontend calls backend APIs using `fetch` or Axios.

Handle:

- Loading state
- Error state
- Empty state
- Success state
- Authentication headers or cookies

Example flow:

```txt
Component mounts -> API call -> Set loading -> Receive data -> Render UI
```

