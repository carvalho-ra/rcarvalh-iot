# K8s GitOps - Inception of Things (P3)

This repository contains Kubernetes manifests deployed via Argo CD on a K3d cluster.

## Structure

- app/
  - deployment.yaml/
  - ingress.yaml/
  - service.yaml/
- argocd
  - application.yaml

## Deployment

kubectl aplly -f argocd/application.yaml

Managed by Argo CD Application defined in the cluster.

## Purpose

GitOps demonstration: declarative deployment of applications using Argo CD.
