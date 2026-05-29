# API Flow

API flow:

```txt
User action -> Set loading -> Call API -> Handle response -> Update UI -> Handle error
```

Always handle:

- Loading
- Error
- Empty response
- Unauthorized
- Validation errors

