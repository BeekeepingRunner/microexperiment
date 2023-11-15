Steps to deploy app in microk8s cluster on localhost:8080:

1. Open terminal in root project folder
2. `microk8s kubectl create -f deployment.yaml`
3. `microk8s kubectl port-forward service/spring-boot-app 8080:80`
