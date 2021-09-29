# k8s学习笔记

## docker

1. dockerfile文件编写
2. 制作小镜像（alpine）
3. 多步骤打包编译


## k8s

### pod

1.create pod

```shell
# 创建pod
kubectl create -f static-pod.yaml

# 更新pod（当yaml更新后，可以通过以下命令更新pod）
kubectl apply -f static-pod.yaml

# 删除pod
kubectl delete po static-pod
```
