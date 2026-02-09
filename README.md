# Kubernetes Networking – Service Types Demo

## Objective
Demonstrate Kubernetes networking concepts using ClusterIP, NodePort,
LoadBalancer, and Ingress with a simple frontend–backend application.

## Architecture
User → Ingress → Service → Pod

## Components
- Frontend: Nginx
- Backend: http-echo
- Services: ClusterIP, NodePort, LoadBalancer
- Ingress: Path-based routing

## Service Types Explained
- ClusterIP: Internal communication
- NodePort: External access via Node IP
- LoadBalancer: Cloud-managed external access

## Routing
- `/` → Frontend
- `/api` → Backend

## Verification
- Access frontend via NodePort
- Access backend via Ingress path `/api`

## Key Learnings
- Services provide stable networking
- Ingress simplifies external routing
- Pods are never accessed directly
