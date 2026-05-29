# Azure Container Registry

Azure Container Registry stores Docker images.

Use ACR for:

- Private container images
- Integration with Azure Pipelines
- Deployment to AKS, App Service, or Container Apps
- Image scanning integrations

Common flow:

```txt
Build image -> Tag image -> Push to ACR -> Deploy image
```

