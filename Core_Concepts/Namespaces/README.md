# Commands

```bash
kubectl get namespaces
# or
kubectl get ns
```

```bash
NAME                 STATUS   AGE
default              Active   23m
kube-node-lease      Active   23m
kube-public          Active   23m
kube-system          Active   23m
local-path-storage   Active   22m
```

```bash
kubectl get pods
```

#### `-n` flag is used to find services in perticular namespace

```bash
kubectl get pods -n kube-system
```

## Creating a Namespace

```bash
kubectl create ns nginx
```

#### Delete a pod

```bash
kubectl delete pod <name-of-the-pod>
```

### Create namespace using menifest file

```yaml
kind: Namespace
apiVersion: v1
metadata:
  name: nginx
```

```bash
kubectl apply -f namespace.yml
```
