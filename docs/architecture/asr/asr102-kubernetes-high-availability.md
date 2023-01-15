# #ASR102-kubernetes-high-availability

## Purpose

The purpose of this requirement is to ensure that the Kubernetes cluster is highly
available and can withstand the failure of one or more of its components.

## Description

The Kubernetes cluster must have a minimum of three master nodes and three worker
nodes. These nodes must be spread across different availability zones or regions
to ensure that the cluster can continue to function in the event of a failure.
The cluster must also have automatic failover capabilities to ensure that the master
nodes are highly available.

## Acceptance Criteria

- [ ] The cluster has a minimum of three master nodes and three worker nodes
- [ ] The master nodes are spread across different availability zones or regions
- [ ] The cluster has automatic failover capabilities for the master nodes
- [ ] The cluster can continue to function in the event of a failure of one or
more components
