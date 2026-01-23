# GKE Cluster – CI-first DevOps Architecture

This repository documents a hands-on platform engineering project
built on GKE using GitHub Actions, KEDA, ArgoCD, and Kubernetes-native tooling (subject to edit).

## Goals
- Build a zero-idle CI platform using KEDA-scaled GitHub runners
- Deploy everything via GitOps
- Implement observability, security, and backup patterns
- Prepare for real-world DevOps / Platform interviews

## Architecture
(placeholder – diagram coming)

## Tools using
- GitHub Actions
- KEDA
- ArgoCD
- k9s
- Prometheus
- Grafana
- Otel
- Add policy-as-code (OPA) if possible


## Status
- [x] GKE cluster created
- [ ] CI namespace & quotas (in progress)
- [ ] KEDA + GitHub runners (in progress)
- [ ] Create the pipelines to use the KEDA github runners and put the policy for the branches
- [ ] Setting up the other repos as submodules
- [ ] Otel &  observability  
- [ ] Prometheus observability
