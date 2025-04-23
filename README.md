# minikube
A closer look at K8s

## Deploying an App

```
kubectl create deployment kubernetes-bootcamp --image=gcr.io/google-samples/kubernetes-bootcamp:v1

```
> This performed a few things for you:
> - searched for a suitable node where an instance of the application could be run (we have only 1 available node)
> - scheduled the application to run on that Node
> - configured the cliuster to reschedule the instance on a new Node when needed

## View the App

> You need to open a second terminal window to run the proxy.

```
kubectl proxy

```

> Now you have a connection between our host (the terminal) & the K8s cluster

> We can now query the version 
