# DevOps Lab Exercises

This repository contains hands-on labs covering containers, Kubernetes, CI/CD, monitoring, and basic shell scripting. Each exercise is in its own directory; screenshots and configuration files are included where available.

## Lab index

| Exercise | Lab | Topics and materials |
| --- | --- | --- |
| 1 | [Kubernetes: Hello Pod]() | Start Minikube, run an Nginx Pod, expose it with a NodePort Service, and test access. Includes a Pod/Service manifest and screenshots. |
| 2 | [Deploy a Flask app on Minikube]()| Build a Flask image in Minikube's Docker environment and deploy it with a Kubernetes Deployment and NodePort Service. |
| 3 | [Scale a Flask app with a ReplicaSet]()| Deploy and scale a flash-sale app, inspect Pod placement, and observe ReplicaSet self-healing. |
| 4 | [Docker networking]() | Build a Flask REST API and explore user-defined bridge networks, container connectivity, and service discovery. |
| 5 | [AppArmor container security]() | Run a Flask app with an AppArmor profile and test restricted actions. |
| 6 | [Delivery monitoring and alerting]()| Collect delivery metrics with Prometheus, define alert rules, and build/run the metrics service through Jenkins. |
| 7 | [Jenkins setup]()| Set up Jenkins in Docker and access its initial setup screen. Screenshots document the exercise. |
| 8 | [Shell script and Git workflow]() | Add a `hello-world.sh` script to a Git repository and push the change to GitHub. |
| 9 | [Jenkins pipeline for a Python app]() | Use a Jenkins pipeline to install dependencies, run unit tests, and stage the Flask app for deployment. |
| 10 | [Kubernetes microservices]() | Build and deploy product-catalog and shopping-cart Flask services with Kubernetes Deployments and Services. |

