\# Dockerized Flask Application on Kubernetes with Minikube



A hands-on DevOps project demonstrating how to containerize a Flask web application using Docker and deploy it on Kubernetes using Minikube.



\## 🚀 Project Overview



This project demonstrates the basic workflow of deploying a containerized Flask application to a local Kubernetes cluster.



The application is packaged as a Docker image, loaded into Minikube, deployed using a Kubernetes Deployment, and exposed through a NodePort Service.



\## 🔄 Deployment Flow



Flask Application

&#x20;       ↓

Docker Image

&#x20;       ↓

Minikube

&#x20;       ↓

Kubernetes Deployment

&#x20;       ↓

Pod

&#x20;       ↓

NodePort Service

&#x20;       ↓

Browser



\## 🛠️ Technologies Used



\- Python

\- Flask

\- Docker

\- Kubernetes

\- Minikube

\- kubectl

\- YAML



\## 📁 Project Structure



```text

minikube-flask-deployment/

│

├── app.py

├── Dockerfile

├── requirements.txt

├── deployment.yaml

├── service.yaml

├── .gitignore

├── README.md

│

└── templates/

&#x20;   └── index.html

