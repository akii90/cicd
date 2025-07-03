# Argo CD install with bitnami chart

## Version

Chart: 9.0.25
Argo CD: 3.0.9

## Install
```shell
kubectl create ns argocd
helm -n argocd upgrade --install -n argocd oci://registry-1.docker.io/bitnamicharts/argo-cd --version 9.0.25 -f values.yaml
```