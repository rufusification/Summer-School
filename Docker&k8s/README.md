# Enable dashboard on MacOS / Windows
```
kubectl create -f https://raw.githubusercontent.com/kubernetes/dashboard/master/src/deploy/recommended/kubernetes-dashboard.yaml
```

```
kubectl get pod --namespace=kubesystem
```

Put the name of the dashbord into command: \
```
kubectl port-forward kubernetes-dashboard-blablabla 8443:8443 --namespace=kube-system
```

