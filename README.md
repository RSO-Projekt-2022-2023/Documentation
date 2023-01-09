# Documentation
Documentation about project.

Documentation about the microservices contained in the organisation.

To congfigure ingress:
```bash
kubectl apply -f hello-world-ingress.yaml 
```

Caution: Before we need to setup ingress on kubernetes service in namespace ingress-basic.

Deploying microservices to kubernetes:
```
kubectl apply -f admin-deployment.yaml --namespace ingress-basic
kubectl apply -f polnilnice-deployment.yaml --namespace ingress-basic
kubectl apply -f searcher-deployment.yaml --namespace ingress-basic
kubectl apply -f vehicles-deployment.yaml --namespace ingress-basic
kubectl apply -f users-deployment.yaml --namespace ingress-basic
kubectl apply -f notifications-deployment.yaml --namespace ingress-basic
``
