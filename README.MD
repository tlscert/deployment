### Bootstrap

1. Bootstrap flux: `kubectl apply --kustomize ./kubernetes/bootstrap`
2. Apply the cluster config: `kubectl apply --kustomize ./kubernetes/flux/config`

### Secrets management

Secrets are currently manually created. When possible this should be switched to 1password with ESO.
