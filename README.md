# Kubernetes Deployment 🚀

## 📌 Overview

This project demonstrates deploying a containerized Flask application to Kubernetes with scaling and service exposure.

## 🏗 Architecture

User → Kubernetes Service → Pods → Flask Containers

## ⚙️ Tech Stack

* Kubernetes
* Docker
* Flask

## 🚀 Features

* Multi-replica deployment
* Service exposure via NodePort
* Environment-based configuration
* Rolling updates
* Scaling support

## ▶️ Deployment Steps

```bash
kubectl apply -f k8s/
```

## 📈 Scaling

```bash
kubectl scale deployment flask-app --replicas=4
```

## 🔄 Rolling Update

```bash
kubectl set image deployment/flask-app flask-container=<image>:v2
```
