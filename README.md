# nbaerts' Helm repository

## How to use this Helm repository

```
helm repo add nbaerts https://nbaerts.github.io/helm-repo/
helm repo update
helm repo list
```

## How to add a package

```
helm package ../local-cluster/charts/*
helm repo index --url https://nbaerts.github.io/helm-repo .
```