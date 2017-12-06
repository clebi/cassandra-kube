# cassandra-kube
Kubernetes cassandra cluster

Deploy a Cassandra cluster using the StatefulSet of Kubernetes. The set will allocate a new storage for each new container when scaling.
An headless service is deployed to get a dns records for Cassandra seeds. There is also a service to make the cluster available outside.

Any modification of the deployment can be achieved through a rolling update.
