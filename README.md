<p align="center">
  <img width="220" src="https://raw.githubusercontent.com/acornops/docs-website/main/logo/light.svg" alt="AcornOps" />
</p>

<h1 align="center">AcornOps Helm Charts</h1>

<p align="center">
  <a href="https://acornops.github.io/charts/index.yaml"><img src="https://img.shields.io/badge/helm_repo-index.yaml-blue.svg" alt="Helm repository index" /></a>
  <img src="https://img.shields.io/badge/chart_source-external-lightgrey.svg" alt="Chart source external" />
</p>

<p align="center">
  Public Helm chart repository for AcornOps.
</p>

## Status

This repository serves the classic `helm repo add` mirror for AcornOps chart
releases. OCI artifacts in GHCR remain the canonical chart release artifacts.

## Usage

```bash
helm repo add acornops https://acornops.github.io/charts
helm repo update
helm search repo acornops
```

## Repository Contents

- `index.yaml`: Helm repository index served by GitHub Pages.
- `*.tgz`: packaged chart releases published by AcornOps release workflows.

Chart source remains in the owning repositories. The platform chart is owned by
`acornops-deployment`; the agent chart is owned by `agentk`.
