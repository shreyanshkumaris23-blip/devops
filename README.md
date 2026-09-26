# 🚀 DevOps Lab Exercises

Welcome to the **DevOps Lab Solutions Repository**! This repository contains hands-on implementations, container configurations, Kubernetes manifests, code samples, step-by-step guides, and **embedded process output screenshots** for the DevOps course lab series.

---

## 📌 Exercises Included

| Exercise | Title | Focus Area | Status | Link |
| :--- | :--- | :--- | :---: | :--- |
| **Exercise 1** | **Kubernetes Getting Started (Hello Pod)** | Pods, NodePort Services, Nginx Deployment | ✅ Completed | [View Exercise 1](Exercise-1/README.md) |
| **Exercise 2** | **Deploy Flask App on Minikube** | Custom Docker Builds, Deployments, YAML | ✅ Completed | [View Exercise 2](Exercise-2/README.md) |
| **Exercise 3** | **Scaling Flask App with ReplicaSets** | Flash Sale Simulation, Scaling, Self-Healing | ✅ Completed | [View Exercise 3](Exercise-3/README.md) |
| **Exercise 4** | **Docker Networking (Multi-Container)** | Bridge Networks, Embedded DNS, Multi-Tier Microservices | ✅ Completed | [View Exercise 4](Exercise-4/README.md) |

---

## 📁 Repository Directory Structure

```
devops/
├── README.md                          # Main repository overview & index
├── Exercise-1/
│   ├── README.md                      # Exercise 1 guide with output screenshots
│   ├── screenshots/                   # Process output screenshots for Exercise 1
│   └── nginx-pod.yaml                 # Nginx Pod & Service manifest
├── Exercise-2/
│   ├── README.md                      # Exercise 2 guide with output screenshots
│   ├── screenshots/                   # Process output screenshots for Exercise 2
│   ├── app.py                         # Python Flask application
│   ├── Dockerfile                     # Docker container configuration
│   └── flask-deployment.yaml          # Deployment & NodePort Service manifest
├── Exercise-3/
│   ├── README.md                      # Exercise 3 guide with output screenshots
│   ├── screenshots/                   # Process output screenshots for Exercise 3
│   ├── app.py                         # Flash Sale Flask application
│   ├── Dockerfile                     # Dockerfile using Gunicorn app server
│   └── flashsale-replicaset.yaml      # ReplicaSet & ClusterIP Service manifest
└── Exercise-4/
    ├── README.md                      # Exercise 4 guide with output screenshots
    ├── screenshots/                   # Process output screenshots for Exercise 4
    ├── app.py                         # Python Flask REST API microservice
    ├── requirements.txt               # Application dependencies
    ├── Dockerfile                     # Container build specification
    └── docker-compose.yml             # Multi-container orchestration compose file
```

---

## 🛠️ Prerequisites & Tools Used

- **Operating System**: Windows / Linux / macOS
- **Container Runtime & Orchestration**: [Docker](https://www.docker.com/) (Engine & Compose)
- **Local Kubernetes Cluster**: [Minikube](https://minikube.sigs.k8s.io/docs/) (v1.34+)
- **Kubernetes CLI**: [kubectl](https://kubernetes.io/docs/tasks/tools/)
- **Programming Languages & Frameworks**: Python 3.8 / 3.9 / 3.11, Flask, Gunicorn
- **Data Stores & Caching**: MySQL 8.x, Redis 7.x

---

## 🔗 Reference Repository
- Reference Source: [SunagP/DevOps-Lab](https://github.com/SunagP/DevOps-Lab)
- Destination Repository: [shreyanshkumaris23-blip/devops](https://github.com/shreyanshkumaris23-blip/devops.git)
