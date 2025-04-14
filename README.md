# Task 5: Kubernetes Cluster with Minikube

## Objective
Deploy and manage a simple Nginx app using Kubernetes on Minikube.

## Tools Used
- Minikube
- kubectl
- Docker

## Steps Performed
1. Started Minikube cluster.
2. Created `deployment.yaml` for Nginx.
3. Exposed app using `service.yaml`.
4. Verified pods and services.
5. Scaled deployment to 4 replicas.

## Screenshots
Check the `screenshots/` folder for CLI outputs.

## Commands Used
```bash
minikube start
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl get pods
kubectl get services
kubectl scale deployment hello-deployment --replicas=4
```
