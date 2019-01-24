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

#### Some useful commands
- Expose pods - `kubectl expose pod nodehelloworld.example.com --type==NodePort`
- Expose service - `kubectl expose pod nodehelloworld.example.com --type==NodePort --name nodehelloworld-service`
- Enter into container shell - `kubectl run -i --tty busybox --image=busybox --restart=N`
- Debug pods
`kubectl attach <podname> -i`
`kubectl exec -it <podname> --bash`
- Watch pods every n seconds `watch -n1 kubectl get pods`
 

#### Resources
1. Fundamentals of Kubernetes: https://lnkd.in/dY25fhp

2. Learning Docker and Kubernetes by Lab
: https://lnkd.in/dbfxZbA

3. Learn DevOps: Advanced Kubernetes Usage: https://lnkd.in/drKJqXb

4. Learn Kubernetes in Under 3 Hours: A Detailed Guide to Orchestrating Containers: https://lnkd.in/d8HDrQD

5. Kubernetes Blog: https://lnkd.in/d9HffNg

6. A Tour of the Kubernetes Source Code Part One: From kubectl to API Server: http://bit.ly/kubetour

7. Kubernetes Tutorial to deploy a load balanced, multi-container application to multiple Kubernetes environments on GKE: https://lnkd.in/dh2ZF2a

8. Google Cloud Platform - Community: https://lnkd.in/dfthbAy

9. Advanced Kubernetes Objects You Need to Know: https://lnkd.in/dzZKRHQ

10. How to move from single master to multi-master in an AWS kopshttp://bit.ly/2LXzEP8

11. Implementing Advanced Scheduling Techniques with Kubernetes: http://bit.ly/2KkNzKb

12. Step by step guide to setup a multi-region Kubernetes app: http://bit.ly/2OCRfdQ

13. Top 10 Kubernetes tips and tricks: https://lnkd.in/dWJqQCs

14. 50 Useful Kubernetes Tools: https://lnkd.in/de5FBTZ
