You can now use the AKS start/stop cluster feature to save costs (public preview).

This feature allows you to completely stop an AKS cluster and pick up where they left off later, saving time and costs.

This new start/stop feature retains cluster configurations, stopping only the control plane and agent nodes.



We will cover more when the feature is generally available.



For more info, refer to the Microsoft documentation below.



Source: https://docs.microsoft.com/en-us/azure/aks/start-stop-cluster



Limitations

When using the cluster start/stop feature, the following restrictions apply:

This feature is only supported for Virtual Machine Scale Sets backed clusters.

During preview, this feature is not supported for Private clusters.

The cluster state of a stopped AKS cluster is preserved for up to 12 months. If your cluster is stopped for more than 12 months, the cluster state cannot be recovered. For more information, see the AKS Support Policies.

During preview, you need to stop the cluster autoscaler (CA) before attempting to stop the cluster.

You can only start or delete a stopped AKS cluster. To perform any operation like scale or upgrade, start your cluster first.

