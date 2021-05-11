# Helm Charts to deploy a K8s nginx application server

### Setup Minikube
`minikube start`

### Create Helm template folder
`helm create hello-world`

### Lint and Template 
```
helm lint ./helm-hello-world
helm template ./helm-hello-world
```

### Install Helm Template
`helm install helm-hello-world ./helm-hello-world`

### Start minikube service
`minikube service helm-hello-world`


[Refer to Baeldung.](https://www.baeldung.com/ops/kubernetes-helm)
