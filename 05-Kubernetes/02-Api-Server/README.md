# Kube Api Server 

```

   86  mkdir 02-Api-Server
   87  ls
   88  kubectl get pods 
   89  kubectl get pods -n kube-system
   90  kubectl cluster-info
   91  kubectl cluster-info dump
   92  kubectl version
   93  kubectl api-versions
   94  kubectl api-resources
   95  kubectl proxy --address='172.31.0.100' --port=8001 --accept-hosts='.' --accept-paths='.' & 
   96  curl 172.31.0.100:8001
   97  curl 172.31.0.100:8001/apis
   98  kubectl api-versions
   99  http://172.31.0.100:8001/api/v1/pods
  100  curl http://172.31.0.100:8001/api/v1/pods
  101  curl http://172.31.0.100:8001/api/v1
  102  curl http://172.31.0.100:8001/api/
```
