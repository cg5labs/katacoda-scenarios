Download (git-clone) the examples: `git clone https://github.com/cg5labs/k8s-examples.git`{{execute}}

Examine the Helm Chart: 
* `cd k8s-examples/`{{execute}}
* `ls -l helm-example2/`{{execute}}

Deploy the Helm Chart: 
* `helm install nginx-example helm-example2`{{execute}}
* `helm list`{{execute}}
* `helm uninstall nginx-example`{{execute}}

![Pods](./assets/module_03_pods.svg)

