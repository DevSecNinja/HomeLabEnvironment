# ASR104-kubernetes-self-healing

## Purpose

The purpose of this requirement is to ensure that the Kubernetes cluster can automatically
detect and recover from failures.

## Description

The Kubernetes cluster must have automatic self-healing capabilities for both nodes
and pods. This means that it should be able to automatically detect and recover from
failures of individual pods, as well as entire nodes. The cluster should also be
able to automatically reschedule failed pods on healthy nodes.

## Acceptance Criteria

- [ ] The cluster has automatic self-healing capabilities for individual pods
- [ ] The cluster has automatic self-healing capabilities for entire nodes
- [ ] The cluster can automatically reschedule failed pods on healthy nodes
