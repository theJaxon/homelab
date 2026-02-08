# homelab
Contains manifests for services that will be running on the local Mkube cluster.

```bash
# Deploy argocd
kustomize build . | kubectl apply --server-side -f -

# Make sure to start by applying argocd first
k apply -f applications/argocd.yaml
```
