Steps to deploy app in minikube cluster

1. Open terminal in root project folder
2. `kubectl apply -f deployment.yaml`
3. Check your cluster IP: `minikube ip`
4. Connect with app on the: `<minikube ip>:31111`
