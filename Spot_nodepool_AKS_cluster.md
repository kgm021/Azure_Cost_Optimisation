You already know what spot VMs are!
A spot node pool in AKS is a node pool backed by a spot virtual machine scale set.

This option allows you to take advantage of unutilized capacity in Azure (spot VMs) at significant cost savings.



## Things to remember:

No SLA for the spot nodes.

A spot node pool is deployed in a single fault domain and hence no high availability.

A spot node pool can't be the cluster's default node pool.



## Useful for:

Workloads that can handle interruptions, early terminations, or evictions.

## Batch processing jobs

Dev / Test environments

Scientific / compute workloads designed to handle interruptions.



Read more about this, refer source below.

Source: https://docs.microsoft.com/en-us/azure/aks/spot-node-pool

