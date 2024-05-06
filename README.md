## Installing Chaos Mesh in Kubernetes Cluster
```curl -sSL https://mirrors.chaos-mesh.org/v2.6.3/install.sh | bash```


## Uninstalling Chaos Mesh from Kubernetes Cluster
```curl -sSL https://mirrors.chaos-mesh.org/v2.6.3/install.sh | bash -s -- --template | kubectl delete -f -```
