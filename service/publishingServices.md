## Publishing services

You must define the service type
- ClusterIp: Expose the service on an internal IP. The service is only visible INSIDE the cluster
- NodePort: Expose the service on each of the node's IP, at a static port
- LoadBalancer: Expose the service externally using a cloud provider's load balancer
- ExternalName: Maps the service to an external name

NOTE: One can use Ingress to expose the service outside the cluster