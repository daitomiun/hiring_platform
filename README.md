# hiring_platform

## how to use

this is an example and a basis for the kubernetes/docker hiring platform following the instructions to make a deployment of the server and instances

After cloning the repo use the following to create the main deployments, services and ingress
```bash
kubectl apply -f .
```

then inside minikube apply the ingress of ngnix for local testing
