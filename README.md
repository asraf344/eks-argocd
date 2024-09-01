# eks-argocd

## Apply argoCD-config
-- Add proper values at `argocm.yaml` for oidc configuration then apply it to your 
k8s cluster.
```shell
$ kubectl apply -n argocd -k  aws-cognito-config
```

