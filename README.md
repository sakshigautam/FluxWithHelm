# FluxWithHelm

.minikube - It is the folder created my Flux after bootstrapping flux with the repo and cluster minikube.

# Subscribe to a Helm Repository

helm repo add ingress-nginx https://kubernetes.github.io/ingress-nginx

## Repository Structure

├── clusters/
│ └── infrastructure/
│ ├── base/
│ │ ├── nginx/
│ │ │ ├── chart.yaml
│ │ │ ├── release.yaml
│ │ │ ├── namespace.yaml
│ │ │ ├── repository.yaml
│ │ │ └── kustomization.yaml
│ │ └── kustomization.yaml
│ └── kustomization.yaml
├── .minikube/
│ ├── kustomizations/
│ │ └── staging/
│ │ ├── staginghelm.yaml
│ │ └── kustomization.yaml
│ └── flux-system/
│ ├── gotk-sync.yaml
│ ├── gotk-components.yaml
│ └── kustomization.yaml




