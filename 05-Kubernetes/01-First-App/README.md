# First App Deployment

```
kubectl get nodes 
kubectl get pods 
```

## Let's deploy Nginx Pod 
```
kubectl run hello-k8s --image=nginx --port=80
kubectl get pods 
kubectl get pods -o wide 
kubectl describe pod hello-k8s
```

