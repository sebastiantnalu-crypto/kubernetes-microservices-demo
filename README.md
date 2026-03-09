# Kubernetes Microservices Deployment

This project demonstrates how to deploy a containerized microservice application using Docker and Kubernetes.

The application is built using Python Flask and deployed as a containerized service orchestrated by Kubernetes.

## Architecture

User → Kubernetes Service → Deployment → Pods → Docker Containers

## Technologies Used

Docker  
Kubernetes  
Python Flask  
REST APIs  
Containerization


## Deployment Steps

Build Docker image

docker build -t microservice-app .

Start Kubernetes cluster

minikube start

Deploy application

kubectl apply -f kubernetes/deployment.yaml

Expose service

kubectl apply -f kubernetes/service.yaml

Check pods

kubectl get pods

## Learning Outcomes

Containerization using Docker  
Microservices architecture  
Kubernetes deployment management  
Service exposure using Kubernetes Services  
Cloud-native application deployment
