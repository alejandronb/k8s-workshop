# k8s-workshop
Repositorio con ejemplos sencillos para trabajar con Kubernetes


Para ejecutar las plantillas del repo:

### POD
```
kubectl apply -f pod.yaml -n <namespace>
```

### REPLICA SET
```
kubectl apply -f replica-set.yaml -n <namespace>
```

### DEPLOYMENT
```
kubectl apply -f deployment.yaml -n <namespace>
```

### STATEFULSET
```
kubectl apply -f statefulset.yaml -n <namespace>
```

### DAEMONSET
```
kubectl apply -f daemonset.yaml -n <namespace>
```

### SERVICE - CLUSTER IP
```
kubectl apply -f service.yaml -n <namespace>
```

### SERVICE - NODE PORT
```
kubectl apply -f service-node-port.yaml -n <namespace>
```


### Comandos útiles
```
kubectl describe pod|deployment|svc -n <namespace>
kubectl get deployment <deployment_name> -o yaml -n <namespace>
kubectl logs <pod_name> -n <namespace>
```
