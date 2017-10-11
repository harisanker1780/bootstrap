## Installing minikube.

```
Install VirtualBox sudo apt-get install virtualbox
Install kubectl sudo snap install kubectl --classic
Install minikube curl -Lo minikube https://storage.googleapis.com/minikube/releases/v0.22.3/minikube-linux-amd64 && chmod +x minikube && sudo mv minikube /usr/local/bin/
```

## Running Kubernetes Locally via Minikube

```
Start minkube minikube start
```

## Starting minikube.

```
sudo -E minikube start --vm-driver=none
sudo chown -R $USER $HOME/.kube
sudo chgrp -R $USER $HOME/.kube
sudo chown -R $USER $HOME/.minikube
sudo chgrp -R $USER $HOME/.minikube
```

## Checking Status
```
minikube status
kubectl get pod
```

## Refer
- https://github.com/kubernetes/minikube
