Pods are the smallest compute unit in K8s. 
* A pod consists of one or more containers
* Containers in a pod share network and can share storage
* Pods follow patterns: Ambassador, sidecar, init-container, ...

Examples:
* `kubectl create pod nginx --image=nginx:alpine -o=yaml --dry-run=client`{{execute}}
* `kubectl create pod nginx --image=nginx:alpine `{{execute}}
* `kubectl get pod nginx --image=nginx:alpine `{{execute}}
