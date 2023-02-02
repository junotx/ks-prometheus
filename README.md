# ks-prometheus

This repository collects Prometheus stack manifests generated from a KubeSphere custom version of [kube-prometheus](https://github.com/prometheus-operator/kube-prometheus.git) and used by KubeSphere cluster monitoring.  

They may be installed by the following command according to your KubeSphere version.  

```shell
kubectl apply -k ./kustomization.yaml
```

> The branch you install should be the same as the branch of KubeSphere version you are using. 
