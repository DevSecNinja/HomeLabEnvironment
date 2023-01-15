# #ASR004-kubernetes-automatic-scaling

## Purpose

The purpose of this requirement is to ensure that the Kubernetes cluster can
automatically scale its resources to meet changing demands.

## Description

The Kubernetes cluster must have automatic scaling capabilities, both horizontally
and vertically. This means that it should be able to automatically add or remove
worker nodes as necessary to meet the demands of the applications running on the
cluster. It should also be able to automatically adjust the resources allocated to
individual pods, such as CPU and memory.

## Acceptance Criteria

- [ ] The cluster has automatic horizontal scaling capabilities for worker nodes
- [ ] The cluster has automatic vertical scaling capabilities for individual pods
- [ ] The cluster can automatically adjust resources to meet the demands of the applications
running on the cluster
