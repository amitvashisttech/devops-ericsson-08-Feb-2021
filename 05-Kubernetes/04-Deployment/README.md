```
  162  cd 05-Kubernetes/
  163  ls
  164  cd 06-Deployment/
  165  ls
  166  vim deployment.yaml 
  167  ls
  168  kubectl create -f deployment.yaml 
  169  vim deployment.yaml 
  170  kubectl api-resources
  171  kubectl get deploy 
  172  kubectl get rc 
  173  kubectl get rs
  174  kubectl get pods 
  175  kubectl scale --replicas=5 deploy helloworld-deployment
  176  kubectl get pods 
  177  kubectl get deplot 
  178  kubectl get deploy 
  179  kubectl get svc 
  180  kubectl expose deploy helloworld-deployment --type=NodePort
  181  kubectl get pods
  182  kubectl get svc 
  183  kubectl get pods -o wide 
  184  kubectl get deplot 
  185  kubectl get deploy 
  186  kubectl describe deploy helloworld-deployment
  187  kubectl describe rs helloworld-deployment-78cf6987f9
  188  kubectl scale --replicas=10 deploy helloworld-deployment
  189  kubectl describe rs helloworld-deployment-78cf6987f9
  190  kubectl scale --replicas=3 deploy helloworld-deployment
  191  kubectl describe rs helloworld-deployment-78cf6987f9
  192  kubectl describe deploy helloworld-deployment
  193  kubectl set image deploy helloworld-deployment k8s-demo=amitvashist7/k8s-tiny-web:2 
  194  kubectl scale --replicas=10 deploy helloworld-deployment
  195  kubectl set image deploy helloworld-deployment k8s-demo=amitvashist7/k8s-tiny-web:3
  196  kubectl get rs 
  197  kubectl get pods 
  198  kubectl describe rs helloworld-deployment-ff6c77c8
  199  kubectl get rs 
  200  kubectl describe rs helloworld-deployment-78cf6987f9
  201  kubectl get rs 
  202  kubectl describe rs helloworld-deployment-558759896c
  203  kubectl get deploy 
  204  kubectl rollout undo deploy helloworld-deployment
  205  kubectl get rs 
  206  kubectl get pods 
  207  kubectl rollout history deploy helloworld-deployment
  208  kubectl rollout undo deploy helloworld-deployment
  209  kubectl rollout history deploy helloworld-deployment
  210  kubectl rollout history deploy helloworld-deployment --revision=1
  211  kubectl rollout history deploy helloworld-deployment --revision=4
  212  kubectl rollout history deploy helloworld-deployment --revision=5
  213  kubectl rollout undo deploy helloworld-deployment --to-revision=1
  214  kubectl rollout history deploy helloworld-deployment
  215  kubectl rollout status deploy helloworld-deployment
  216  kubectl rollout undo deploy helloworld-deployment 
  217  kubectl rollout status deploy helloworld-deployment
  218  kubectl rollout history deploy helloworld-deployment
  219  kubectl set image deploy helloworld-deployment k8s-demo=amitvashist7/k8s-tiny-web:4 --record
  220  kubectl rollout status deploy helloworld-deployment
  221  kubectl rollout history deploy helloworld-deployment
  222  kubectl rollout history deploy helloworld-deployment --revision=8
```
