ClusterIP. Exposes a service which is only accessible from within the cluster.
NodePort. Exposes a service via a static port on each node's IP.
LoadBalancer. Exposes the service via the cloud provider's load balancer.





The Service "service-app" is invalid: spec.ports[0].nodePort: Invalid value: 3000: provided port is not in the valid range. The range of valid ports is 30000-32767
