# k8sDeployment

#### WIP
Solution for deploying FileFighter to [Kubernetes](https://kubernetes.io/).




https://twitter.com/ctrlshifti/status/1322859969872449536


To apply this do:  
```
kubectl apply -f frontend.yaml
kubectl apply -f secret.yaml 
kubectl apply -f database.yaml 
kubectl apply -f rest.yaml 
```


If you don't have a Kubernetes Cluster you can also use [Minikube](https://v1-15.docs.kubernetes.io/docs/tasks/tools/install-minikube/) to test it.