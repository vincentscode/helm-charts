# helm-charts

This repository contains helm charts for deploying applications on Kubernetes.
It consists of charts created or modified by me for use in [my home lab](https://github.com/vincentscode/infra).

## Usage
```bash
helm repo add vincentscode https://vincentscode.github.io/helm-charts/
helm search repo vincentscode
```

## Notes
### Creating a new chart
```bash
cd charts
helm create <chart-name>
rm -rf <chart-name>/charts
```

### Packaging a chart
Charts are packaged automatically by github actions using the [helm/chart-releaser-action](https://github.com/helm/chart-releaser-action).
