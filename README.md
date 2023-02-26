### Deployment Commands

Deployment - create replica which will manage pods

```bash
kubectl apply -f nginx-deploy.yaml
```

Service - create entry point to container

```bash
kubectl apply -f nginx-service.yaml
```

Ingress - manage service ingression

```bash
kubectl apply -f nginx-ingress.yaml
```

### Monitor Commands

### Delete Object

```bash
kubectl delete -f nginx-deploy.yaml
```
