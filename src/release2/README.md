# Application System Release 2

## Changes From Release 1

* Some updates to the web app

## How To Use

* Start a terminal session with kubectl installed and configured to connect to a running Kubernetes cluster where you have access to the default namespace
* Navigate to this directory where the Kubernetes YAML files are located
* To create / deploy resources, execute the following command
```
kubectl apply -f .
```
* To delete resources, execute the following command
```
kubectl delete -f .
```