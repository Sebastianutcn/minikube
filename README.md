# minikube
A simple way to expose a service to the internet

Commands for exposing to the internet: 
   - make sure that minikube is installed
   - Docker Desktop is opened
1. minikube start
2. kubectl apply -f deployment.yml
3. kubectl apply -f service.yml
4. minikube service mytodoapp-service
