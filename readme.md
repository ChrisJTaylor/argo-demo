```
argocd app create argo-demo-dev --repo https://github.com/ChrisJTaylor/argo-demo.git --path development --dest-server https://kubernetes.default.svc --dest-namespace argo-dev
```

```
argocd app create argo-demo-prd --repo https://github.com/ChrisJTaylor/argo-demo.git --path production --dest-server https://kubernetes.default.svc --dest-namespace argo-prd
```