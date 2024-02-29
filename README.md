+ `kubectl config get-contexts` - to check all available contexts
+ `kubectl config use-context docker-desktop` - to switch to expected context
+ `kubectl apply -f platforms-depl.yaml` - create deployment (start containers)
+ `kubectl get deployments` - show deployment list
+ `kubectl get pods` - show pods
+ `kubectl delete deployment platforms-depl` - delete deployment (stop all containers)
+ `kubectl apply -f platforms-nodeport-srvc.yaml` -  route external traffic on NodePort to the pods running the <br> platformservice Deployment on port 80.
+ `kubectl get services` - show services and returned ports.
+ `kubectl delete service platformsnodportservice` - delete deployment (stop all containers)