# Azure Resource Model

Important hierarchy:

```txt
Tenant -> Management group -> Subscription -> Resource group -> Resource
```

Subscription:

- Billing and access boundary.

Resource group:

- Logical container for related resources.

Resource:

- Actual Azure service instance, such as VM, storage account, or App Service.

Good habit:

```txt
Group resources by application, environment, or lifecycle.
```

