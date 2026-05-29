# File Upload

Common file upload flow:

```txt
Frontend selects file -> Backend validates file -> Store file -> Save URL in database
```

Storage options:

- Local disk for learning
- Cloudinary
- S3-compatible storage

Validate:

- File type
- File size
- Auth permission

