# Jellyfin Helm Chart

Helm chart for deploying Jellyfin in a Kubernetes cluster.

## Purpose
This repository contains a Helm chart used to deploy Jellyfin via Argo CDas part of a GitOps-managed homelab.

## Usage
This chart is not installed directly with `helm install`. It is consumed by Argo CD from a separate GitOps repository.

## Notes
- The chart is namespace-agnostic.
- Namespace creation and placement are handled by Argo CD.
- Persistent storage is expected to be provided via PVCs.

This chart is intended for personal use in a homelab environment.

