### What is Kubernetes
 - Open source orchestration system for Docker containers
 - Lets you schedule containers on a cluster of machines
 - You can run multiple containers on one machine
 - It can manage the state of these containers (starts the conainer on specific node, restart the container when it gets killed, moves container from one node to another 
 - Instead of running few docker containers on one host manually, Kubernetes platform will manage the containers for you
 - You can run Kubernetes On-premise, Public(Google Cloud, AWS), Hybrid(Public and Private)
 

# kubernetes (running minikube locally on Windows)
Download the https://storage.googleapis.com/minikube/releases/latest/minikube-windows-amd64.exe 'minikube-windows-amd64.exe' file, rename it to minikube.exe and add it to your path.

```
$ minikube start
```

#### For Ubuntu
Download the debian package from https://github.com/kubernetes/minikube/releases and run
```
$ sudo dpkg -i minikube_.deb
```
