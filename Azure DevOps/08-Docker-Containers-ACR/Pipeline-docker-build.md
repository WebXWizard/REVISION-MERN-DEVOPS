# Pipeline Docker Build

Pipeline steps:

1. Checkout code.
2. Install dependencies if needed.
3. Build Docker image.
4. Run tests.
5. Tag image.
6. Login to ACR through service connection.
7. Push image.
8. Deploy image to target.

Important:

- Keep registry credentials secure.
- Scan images if possible.
- Publish build metadata.

