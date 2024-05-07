```bash
kubectl create -f clusterrolebinding.yaml
kubectl create -f composition.yaml
kubectl create -f definition.yaml
kubectl create -f xr.yaml

sleep 60

kubectl create -f object.yaml
```