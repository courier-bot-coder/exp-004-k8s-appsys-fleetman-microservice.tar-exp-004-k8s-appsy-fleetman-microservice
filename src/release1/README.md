# Application System Release 1

* Have to deploy in the K8s default namespace because application code hardcode hostnames
  * fleetman-api-gateway.default.svc.cluster.local
  * fleetman-queue.default.svc.cluster.local
  * fleetman-position-simulator.default.svc.cluster.local
  * fleetman-position-tracker.default.svc.cluster.local