## Commands

#### How to enter into pod

```bash
kubectl exec -it pod/nginx-pod -n nginx -- bash
```

#### Describe your pod/ check more information about pod

#### If pod or any service is running in perticular namespace then use `-n` and name of the namespace

```bash
kubectl describe pod/<name-of-the-pod> -n <name-of-namespace>
```
