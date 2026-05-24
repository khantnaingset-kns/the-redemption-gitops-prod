# The Redemption Platform - Production GitOps

This repository contains the production GitOps desired state for the **Accor Redemption Platform** assessment.

It manages Kubernetes platform components and application workloads through Argo CD using a production-style separation between:

- cluster infrastructure components
- application workloads
- Argo CD projects and deployment boundaries
- Karpenter capacity definitions
- observability and policy controls

The repository is designed for the `prod` environment.