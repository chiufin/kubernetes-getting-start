# Kubernetes

自動部署, 擴充, 操作 container 的 open source 平台

## 特色
1. 快速 deploy

2. 迅快的 scale

3. 滾動上架新的 feature

4. 較少使用 硬體資源


## Components

1. Master Node
    - kube-apiserver
    - etcd
    - addons
    - ... 

2. Node Components
    - kubelet
    - kube-proxy
    - docker
    - ...



## API
    ...

## Objects

#### apiVersion 
使用幾版的 Kubernetes API，去產生這個 object

#### kind
object 種類

#### metadata
`name`
`namespace` 
`spec` 不同 obj 不同 format


每個 object 擁有兩個 nested object 去主宰 object 的狀態
- `spec`
- `status`


