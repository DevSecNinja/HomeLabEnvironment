# #ASR101-kubernetes-best-practices

## Purpose

The purpose of this requirement is to ensure that the Kubernetes cluster is deployed
using best practices that are widely accepted and tested in production environments.

## Description

The Kubernetes cluster must be deployed using a method that follows the Kubernetes
Operations (KOPS), kubeadm or similar industry standard tooling. This will ensure
that the cluster is deployed in a consistent and repeatable way, and that it meets
the necessary reliability, scalability, and security requirements.

## Acceptance Criteria

- [ ] The cluster is deployed using a tool such as KOPS or kubeadm
- [ ] The cluster adheres to the Kubernetes cluster best practices as outlined
in the Kubernetes documentation
- [ ] The cluster can be easily recreated and scaled as necessary
