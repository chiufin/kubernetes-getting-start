# Kubectl document

## Prerequisites
使用 minikube 當作範例
## 名詞解釋

1. Node 

2. Pod 

3. [Service](https://kubernetes.io/docs/concepts/services-networking/service/)

4. Deployment

5. [Secrets](https://kubernetes.io/docs/concepts/configuration/secret/)

6. Volumes 儲存container資料 可以放在 pod / node


## 最常使用的指令

1. kubectl get ... (ex. nodes , pods, services, secrets)

2. kubectl describe ... (ex. secrets/db-user-pass)

3. kubectl create ...

4. minikube ...



## Build Yaml
build pods, services, deployments, ...
```
kubectl create -f ./my-first-pod.yaml
kubectl create -f ./my-service.yaml
kubectl create -f ./my-secret.yaml
```

## Build with CMD
```
kubectl expose pod my-pod --type=NodePort --name=my-service 
```

## Get Url
```
minikube service my-service  --url
```