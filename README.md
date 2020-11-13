# k3s-charts

## apache

### install
```
helm install apache ./apache -n apache --create-namespace
```

### uninstall
```
kubectl delete ns apache
```

## longhorn

### install
```
helm install longhorn ./longhorn -n longhorn-system --create-namespace
```
