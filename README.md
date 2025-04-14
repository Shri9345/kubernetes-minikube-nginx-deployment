# kubernetes-minikube-nginx-deployment
✅ Description:
A brief summary of what the task does.

✅ Tech Stack:
- Kubernetes
- Minikube
- kubectl
- Docker
- Ubuntu 22.04 (EC2)

✅ Steps Covered:
1. Installed Docker, Minikube, kubectl on EC2
2. Started Minikube with Docker driver
3. Created deployment.yaml to deploy nginx
4. Created service.yaml to expose nginx on NodePort
5. Verified pods and services using kubectl
6. Scaled the deployment
7. Described and fetched logs from pods

✅ How to Run:
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl get pods
kubectl get svc
