# k8s-workshop
Repositorio con ejemplos sencillos para trabajar con Kubernetes


Para ejecutar las plantillas del repo:

### POD
```
kubectl apply -f pod.yaml
```

### REPLICA SET
```
kubectl apply -f replica-set.yaml
```

### DEPLOYMENT
```
kubectl apply -f deployment.yaml
```

### STATEFULSET
```
kubectl apply -f statefulset.yaml
```

### DAEMONSET
```
kubectl apply -f daemonset.yaml
```

### SERVICE - CLUSTER IP
```
kubectl apply -f service.yaml
```

### SERVICE - NODE PORT
```
kubectl apply -f service-node-port.yaml
```


### Comandos útiles
```
kubectl describe pod|deployment|svc
kubectl get deployment <deployment_name> -o yaml
kubectl logs <pod_name>
```
