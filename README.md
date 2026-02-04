# Cloud-Native AI SaaS Deployment

Production-grade deployment of transformer-based NLP models using Kubernetes, GitOps, and CI/CD.

## Stack
FastAPI, Transformers, Docker, Kubernetes, Argo CD, GitHub Actions

## Run locally
docker build -t nlp-inference services/nlp-inference
docker run -p 8080:8080 nlp-inference