# Guestbook – Inlämningsuppgift OpenShift / Helm / GHCR / ArgoCD


.
├── .github
|   └── workflows
|       └── build-images.yaml
├── argocd
│   └── deployment.yaml
├── backend
│   ├── Dockerfile.backend
│   ├── go.mod
│   └── main.go
├── frontend
│   ├── Dockerfile.frontend
│   ├── index.html
│   └── nginx.conf
├── helm
│   └── guestbook
│       ├── Chart.yaml
│       ├── templates
│       │   ├── backend.yaml
│       │   ├── config-secret.yaml
│       │   ├── frontend.yaml
│       │   ├── postgresql.yaml
│       │   ├── redis.yaml
│       │   └── route.yaml
│       └── values.yaml
└── README.md

