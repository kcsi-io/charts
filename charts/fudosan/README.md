# Fudosan chart

Create docker secret to download images:

```bash
kubectl create secret docker-registry --from-file=.dockerconfigjson=test.json ghcr.io
```