## Install minikube

## Install kubectl 

```
curl -LO https://storage.googleapis.com/kubernetes-release/release/v1.17.0/bin/darwin/amd64/kubectl && chmod +x ./kubectl && sudo mv ./kubectl /usr/local/bin/kubectl
```
Test that it works
```
kubectl version --client
```

## Install minikube

Install hyperviser
```
brew install hyperkit
```
Install minikube
```
brew install minikube
```
Start minikube
``` 
minikube start --vm-driver=hyperkit
```

See https://kubernetes.io/docs/tasks/tools/install-minikube/ for more detils.
