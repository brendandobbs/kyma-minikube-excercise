# Kyma on Minikube

## Install kubectl

1. Download kubectl
https://storage.googleapis.com/kubernetes-release/release/v1.14.6/bin/windows/amd64/kubectl.exe

2. Add the binary in to your PATH.
3. Test to ensure the version of kubectl is the same as downloaded:
```
kubectl version --client
```
## Install minikube

1. Download installer
https://storage.googleapis.com/minikube/releases/latest/minikube-installer.exe

https://minikube.sigs.k8s.io/docs/start/windows/

## Start minikube
```
minikube start --vm-driver=virtualbox
```

## Provision Kyma
```
kyma provision minikube
```
