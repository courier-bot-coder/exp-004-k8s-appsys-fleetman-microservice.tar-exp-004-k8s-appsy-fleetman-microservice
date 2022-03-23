# Microservices Using Kubernetes Tutorial By Richard Chesterwood

The Kubernetes resources have to deployed in "default" namespace.  The app components uses the default.svc.cluster.local for DNS name resolution:

* fleetman-api-gateway.default.svc.cluster.local
* fleetman-queue.default.svc.cluster.local
* fleetman-position-simulator.default.svc.cluster.local
* fleetman-position-tracker.default.svc.cluster.local


## Docker Hub Images
```
docker pull richardchesterwood/k8s-fleetman-queue:release2
docker pull richardchesterwood/k8s-fleetman-position-simulator:release2
docker pull richardchesterwood/k8s-fleetman-position-tracker:release2
docker pull richardchesterwood/k8s-fleetman-webapp-angular:release2
```

## Source Code

* [Dick Chesterwood K8s Fleetman (GitHub)](https://github.com/DickChesterwood/k8s-fleetman)
* A copy is located under src/k8s-fleetman
* Can work with source code using Visual Studio Code development container
* The devcontainer configured used Red Hat UBI linux distro.  To pull RPM software packages, use "sudo microdnf" as the package manager client
* To build software provided, need to install ng npm package: 
    ```
    npm install ng
    npm run build
    ```
