# Kubectl                                                                                                                                                                                     
## Cluster

>(Cluster Info $) **`kubectl cluster-info`** 

>(Status components $) **`kubectl get componentstatuses`** 

>(Configuration $) **`kubectl config view`** 

>(Api $) **`kubectl api-resources`** 

>(List everithing $) **`kubectl get all`** 

>(List of contexts $) **`kubectl config get-contexts`**

>(Current context $) **`kubectl config current-context`**

>(Switch context $) **`kubectl config use-context <name>`**

## Deployments

>(List deployments $) **`kubectl get deployments`**

>(List deployment $) **`kubectl get deployments <name>`**

>(List deployment and export$) **`kubectl get deployments <name> -o yaml or json`**

>(Describe deployment) **`kubectl describe deployment <name>`**

>(Edit deployment) **`kubectl edit deployment <name>`**


##Events

>(List events $) **`kubectl get events`**

>(List events order time$) **`kubectl get events --sort-by='.metadata.creationTimestamp' -A`**
