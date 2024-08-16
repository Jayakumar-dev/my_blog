---
title: ☸️Kubernetes Architecture Overview
summary: Kubernetes has revolutionized the way we manage and scale containerized applications. 
date: 2024-08-16
authors:
  - Jayakumar
tags:
  - Kubernetes
  - Architecture
image:
  caption: Kubernetes Overview
---

## Let's break down its architecture:

## 🚀Master Node (Control Plane):

🫀API Server (kube-apiserver): The entry point to the Kubernetes cluster, exposing the Kubernetes API for all interactions.

🕸️Scheduler (kube-scheduler): Allocates pods to nodes based on resource availability and constraints.

👩‍🔧Controller Manager (kube-controller-manager): Runs essential controllers like the replication and endpoint controllers, ensuring the cluster’s desired state.

🧠ETCD-Database: A distributed key-value store that holds the cluster's state and other Informations.


## 💪💪Worker Nodes:

🧟Kubelet: Ensures the containers in the pods are running and reports the node’s status back to the control plane.

💬Kube-proxy: Manages network rules on nodes, enabling communication to and from pods.

🐳Container Runtime: The software that runs the containers, such as Docker or containerd.
With this architecture, Kubernetes provides a robust and flexible framework for deploying, scaling, and managing applications in a microservices environment.

Check-out the artist work below😂😂🙌


## Did you find this page helpful? Consider sharing it 🙌
