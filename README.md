# Prereq

Install helm

# Install Vector
```
helm repo add vector https://helm.vector.dev
helm repo update
helm install vector vector/vector   --namespace tekton-pipelines   --create-namespace   --values values.yaml
```
