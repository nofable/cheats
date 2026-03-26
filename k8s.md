```bash
# change context
kubectl config use-context <context>
# get nodes
kubectl get nodes
# get pods
kubectl get pods
# get pods with more detail
kubectl get pods -o wide
# run nginx
kubectl run nginx --image=nginx --port=80
# delete the pod
kubectl delete pod nginx
# execute a command
kubectl exec -it nginx -- curl localhost
# create a deployment
kubectl create deployment nginx --image=nginx --replicas=2
# Delete the deployment
kubectl delete deployment nginx
```
