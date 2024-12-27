This is an example Kubernetes deploy for Ludivault.

Note that for the production deployment you must modify database configuration, provide https and an ingress controller.

The database is also configured with a simple persistent volume. You might want to consider using some other form of storage or an entire database service outside of k8s to have a better performance/reliability.

