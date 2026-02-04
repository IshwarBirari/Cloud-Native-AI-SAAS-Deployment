# Cloud-Native AI SaaS Deployment

Production-grade deployment of transformer-based NLP models using Kubernetes, GitOps, and CI/CD.

## Stack
FastAPI, Transformers, Docker, Kubernetes, Argo CD, GitHub Actions

## Run locally
docker build -t nlp-inference services/nlp-inference
docker run -p 8080:8080 nlp-inference

KEY FEATURES:-
- Transformer-based NLP sentiment analysis
- FastAPI-powered inference API
- Confidence score generation for predictions
- Dockerized microservice architecture
- Kubernetes deployment with Services and HPA support
- Browser-based chat-style UI
- Secure cross-origin API communication (CORS enabled)
- Real-time inference via REST API

TECH STACK SECTION:-
- **Backend:** FastAPI, Python
- **ML Model:** HuggingFace Transformers
- **Containerization:** Docker
- **Orchestration:** Kubernetes
- **Frontend:** HTML, CSS, JavaScript
- **Deployment:** Kubernetes Services, Port Forwarding

