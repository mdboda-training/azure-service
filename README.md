# azure-service


To use this you should have the following installed in your machine
1. Docker
2. K8s (For Winds you should install choco from the link copy the highlighted command in you powershell
3.   https://chocolatey.org/install
![image](https://github.com/user-attachments/assets/5b21a7f9-63e4-4dda-a270-3bbc0fe27f49)
  and Follow the commands
4. choco install kubernetes-cli
5. choco install minikube
6. minikube start
7. After testing the complete application you can stop minikube command: minikube stop

Post installation follow the steps
the below files deployment.yaml and service.yaml will be available in k8s folder
kubectl apply -f deployment.yaml 
kubectl apply -f service.yaml

check in your localhost
http://localhost:8080
