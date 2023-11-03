##To run :
1. minikube start
2. kubectl apply -f Deployment.yaml
3. kubectl apply -f Service.yaml
4. Get minikube ip - minikube ip
5. Get node-port - kubectl get services
6. access it here - http://<minikube-ip>:<node-port>
