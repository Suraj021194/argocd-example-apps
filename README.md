1. Project Overview
Title: ArgoCD GitOps with App of Apps Pattern

Description: Demonstrates a production‑ready GitOps workflow using ArgoCD, Helm, and the App of Apps pattern to manage multiple environments (dev, staging, prod).

Key Features:

Parent Application (app-of-apps) manages child apps.

Automated sync with prune/self‑heal.

Multi‑environment Helm deployments.

RBAC troubleshooting and repo hygiene.

2.Architecture Diagram
![](/home/suraj/Documents/ParentApplication.png)
“The App-of-Apps parent manages child applications (dev, staging, prod). Each child points to the same Helm chart with environment-specific values, and all workloads are deployed into the Kubernetes cluster.”
