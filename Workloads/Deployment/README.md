## commands

#### If you want to see deplyment in the perticuler namespace

```bash
kubectl get deployment -n nginx
```

#### If you want to scale your pods

```bash
kubectl scale deployment/nginx-deployment -n nginx --replicas=5
```

## Deployment provides Rolling updates

---

```bash
kubectl get pods -n nginx -o wide
```

---

#### Check more information about all the pods

So kubernetes doesn't down all the pods while updating any thing of your serivce but it keep running pods while parallaly it's update your service or let's say any error came it'll still keep up and running you application.

##### How to to do this:

```bash
kubectl set image deployment/nginx-deployment -n nginx nginx=nginx:1.27.3
```

#### Delete the deployment

```bash
kubectl delete -f deployment.yml
```
