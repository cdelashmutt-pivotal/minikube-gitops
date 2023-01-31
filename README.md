# minikube-gitops

This repo is monitored by kapp-controller at the "config" path to apply any manifests that show up there on the main branch.

## Bootstrap
kubectl apply -f https://raw.githubusercontent.com/cdelashmutt-pivotal/minikube-gitops/main/kapp/gitops-app.yaml