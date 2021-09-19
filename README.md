# Microservice-Using-Istio
Repository for the "Securely Exposing A Microservice-based E-commerce Application To The Internet Using Istio" Manning liveProject.


Istio-Sidecar Injection

kubectl label namespace online-boutique istio-injection=enabled --overwrite

Istio Installation

https://istio.io/latest/docs/setup/install/istioctl/


Delete from Current Namespace

kubectl delete daemonsets,replicasets,services,deployments,pods,rc --all


Delete from all Namespaces

kubectl delete all --all --all-namespaces
