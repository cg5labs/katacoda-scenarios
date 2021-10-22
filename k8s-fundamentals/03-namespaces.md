Kubernetes workloads are organized in namespaces. Most k8s resources can be allocated to namespaces, only a few resources are on cluster-level. A special namespace is **kube-system** , the default K8s namespace for resources that are in the cluster Control Plane.

Namespaces:
* Create logical partition within the cluster
* Control access to k8s resources (pods, services, ...)
* Can limit resource consumption (CPU,Memory) for workloads
* Use labels to further organize resources inside the namespace

Try:
* `kubectl get namespaces`{{execute}}
* `kubectl get all --namespace=default`{{execute}}

