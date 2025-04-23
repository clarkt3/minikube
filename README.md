# minikube
A closer look at K8s

## Deploying an App

```
kubectl create deployment kubernetes-bootcamp --image=gcr.io/google-samples/kubernetes-bootcamp:v1

```
> This performed a few things for you:

> - searched for a suitable node where an instance of the application could be run (we have only 1 available node)
> - scheduled the application to run on that Node
> - configured the cluster to reschedule the instance on a new Node when needed
