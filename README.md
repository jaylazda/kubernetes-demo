# kubernetes-demo

To deploy to kubernetes cluster without helm:
Make sure minikube or Docker Desktop is installed and there is a cluster running.

kubectl create -f deploy-hello.yaml
kubectl create -f service-hello.yaml

App will be deployed and service will be exposed on localhost:8080

To deploy using helm chart:
Install helm.

helm install chart-hello ./chart-hello

App will be deployed and service will be exposed on localhost:8080
