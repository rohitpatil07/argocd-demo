# argocd-demo
# Access Argo-CD Dashboard
```
microk8s kubectl port-forward -n argocd  svc/argocd-server 8080:443
```
# Having problems deploying applications
Consider running 
```
microk8s kubectl apply -f coredns
```