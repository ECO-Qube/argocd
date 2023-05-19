# ArgoCD GitOps repository

This repository contains the repository for ArgoCD in ECO-Qube project. ArgoCD Autopilot was used.

## Deployment sites

There is currently one deployment site available in Blockheating, other additional sites can be added.

## Overview of applications

Some resources are not managed by ArgoCD at the moment, specifically:
- Telemetry Aware Scheduler
- Custom Metrics API Server
- Prometheus
- Calico CNI

The others are all managed by K8s:
- ArgoCD 
- Argo CD Image Updater 
- Job Submission Platform
- Target Exporter
- Prometheus and Adapter ConfigMaps 
