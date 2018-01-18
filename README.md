# Kubectl document

使用 minikube 當作範例

最常使用的指令

1. kubectl get ...

2. kubectl describe ...

3. kubectl create ...

4. minikube



## Build Pod
```
kubectl create -f ./my-first-pod.yaml
```

## Build [service](https://kubernetes.io/docs/concepts/services-networking/service/)
```
kubectl create -f ./my-service.yaml
```

```
kubectl expose pod my-pod --type=NodePort --name=my-service 

minikube service my-service  --url

```