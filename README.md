# homelab
Contains manifests for services that will be running on the local Mkube cluster.

```bash
kustomize build . | kubectl apply --server-side -f -
```
