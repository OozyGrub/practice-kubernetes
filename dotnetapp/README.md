## Requirements

- Company want to deploy dotnetcore application with configurable appsettings on Kubernetes Cluster with HA .
- 3 Instance is require.
- Developer want to access application with path /dotnetapp

### Tasks

1. Create Configmap with .netcore appsettings provide.
2. Deploy .netcore Application with 3 Pod. Use Docker Image [mcr.microsoft.com/dotnet/samples:aspnetapp](http://mcr.microsoft.com/dotnet/samples:aspnetapp)
   and mount appsettings to /app/appsettings.json
3. Create Service Type ClusterIP and Select dotnetcore application.
4. Create Ingress path /dotnetapp and route to application
