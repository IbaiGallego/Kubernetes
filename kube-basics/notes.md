## Pods

### Download the .yml to the VM
```
git clone "link"
```
### run .yml command to create pod
```
kubectl create -f sample-node-app.yml
```
### Returns Pods
```
kubectl get pods
```
### Logs of selected object
```
kubectl logs sample-node-app
```
### Details about pod
```
kubectl describe pod sample-node-app
```

### Delete pod
```
kubectl delete name
```

### Run and connect to the pod
```
kubectl exec -it sample-node-app sh
```

## Replica Sets

### Get replica set
```
kubectl get rs
```