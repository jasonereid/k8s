# Kubernetes administration and security

## Kubectl - Command Line Cheat Sheet

## Add or remove stuff
kubectl create - *creates resources, add -f file.yaml to create from file*

kubectl delete - *deletes resources*

kubectl apply -f ./manifest.yaml - *manifests can be yaml, yml, and .json*

## Find and view resources
kubectl get pods - *gets the status of your pods*

kubectl get services 

kubectl get nodes

kubectl describe pods

## Logs
kubectl logs 

kubectl logs my-k8-pod

kubectl top pod my-k8-pod --sort-by=cpu


kubectl config - *allows you to see and change which cluster you are communicating with*

