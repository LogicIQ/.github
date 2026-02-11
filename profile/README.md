# LogicIQ

[Website](https://logiciq.ca)

Cloud-native Kubernetes operators and tools for modern infrastructure automation.

## 🚀 Projects

### [pvc-chonker](https://github.com/LogicIQ/pvc-chonker)
Cloud-agnostic Kubernetes operator for automatic PVC expansion. Works with any CSI-compatible storage without external dependencies.

### [secret-santa](https://github.com/LogicIQ/secret-santa)
Kubernetes operator for sensitive data generation with Go template support. Generate secrets directly in-cluster without storing them in Terraform state.

### [konductor](https://github.com/LogicIQ/konductor) 
Kubernetes operator for workflow coordination and job orchestration. Synchronize Jobs, coordinate multi-stage pipelines, and manage complex workflows.

### [helm-charts](https://github.com/LogicIQ/helm-charts)
Official Helm charts repository for all LogicIQ Kubernetes operators and tools.

## 📦 Installation

All operators are available via Helm:

```bash
helm repo add logiciq https://logiciq.github.io/helm-charts
helm repo update
```

