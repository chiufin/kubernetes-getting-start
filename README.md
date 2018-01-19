# Kubectl document

使用 minikube 當作範例
## 名詞解釋

1. Node 

2. Pod 

3. Service

4. Deployment

5. Secrets



## 最常使用的指令

1. kubectl get ... (nodes , pods, services)

2. kubectl describe ... 

3. kubectl create ...

4. minikube ...



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