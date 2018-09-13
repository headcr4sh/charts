# Kubedex charts library

To use this charts repository

```
helm repo add kubedex https://kubedex.github.io/charts
helm repo update
```

# Development

1. Update the version in `Chart.yaml`
2. `helm package kubedex-exporter`
3. `mv kubedex-exporter-0.0.x.tgz docs/`
4. `helm repo index docs --url https://kubedex.github.io/charts`
5. Commit and push to master
