Pods are the smallest compute unit in K8s. 
* A pod consists of one or more containers
* Containers in a pod share network and can share storage
* Pods follow patterns: Ambassador, sidecar, init-container, ..

Note: `kubectl` uses profiles (contexts) that set defaults (e.g. for namespace)

Examples:
* `kubectl run nginx --image=nginx:alpine -o=yaml --dry-run=client`{{execute}}
* `kubectl run nginx --image=nginx:alpine --namespace=default`{{execute}}
* `kubectl get pod nginx`{{execute}}
* `kubectl get pod --namespace=default`{{execute}}
