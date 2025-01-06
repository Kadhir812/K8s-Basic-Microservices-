# Kubernetes Microservices Project

## Overview
This project demonstrates a microservices application deployed on Kubernetes. It consists of:
1. **User Service** (Python Flask)
2. **Order Service** (Node.js Express)
3. **MySQL Database**

## Features
- User and Order management.
- Internal DNS for service-to-service communication.
- Persistent storage for MySQL.
- Scalability with Kubernetes.

## Architecture
The project uses Kubernetes for deployment with the following architecture:
- **User Service**: Handles user data.
- **Order Service**: Manages orders and communicates with the User Service.
- **MySQL**: Stores user and order data.

## Prerequisites
- Docker
- Kubernetes (Minikube, kubectl, or a managed cluster)
- MySQL client
- Node.js and Python

## Steps to Deploy

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/kubernetes-microservices.git
cd kubernetes-microservices
