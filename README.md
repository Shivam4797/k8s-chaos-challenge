# k8s-chaos-challenge
Progressive chaos engineering on Kubernetes (AWS EKS) with Ansible + CI/CD.

## Goal
Design a Kubernetes-driven chaos framework that escalates failures by levels and validates resilience, auto-healing, and SLO compliance under load.

## Tech Stack
Kubernetes (EKS) · Ansible · LitmusChaos · Prometheus · Grafana · Jenkins/GitHub Actions 

## Chaos Levels (v0)
L1: single pod delete · L2: multi-pod + latency · L3: node disruption · L4: combined faults

## SLOs (draft)
- Availability ≥ 99.9% during tests
- p95 latency < 200 ms under load
- Error rate < 1% sustained

## Status
🚧 Planning → Environment setup next.

