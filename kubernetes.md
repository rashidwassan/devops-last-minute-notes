# Kubernetes

## Introduction:
Kubernetes is an open-source platform designed to automate deploying, scaling, and operating application containers.
Google originally developed it and is now maintained by the Cloud Native Computing Foundation (CNCF).

## Key Concepts
`Pods:` The smallest deployable units in Kubernetes, comprising one or more containers.

`Deployments:` A higher-level abstraction that manages Pods and provides features like scaling, rolling updates, and rollback.

`Services:` An abstraction that defines a logical set of Pods and policies to access them, allowing communication between Pods.

`Nodes:` Machines (physical or virtual) in a Kubernetes cluster that run Pods.

`Clusters:` A collection of nodes that Kubernetes manages.

### Some More Concepts
`Objects:` Kubernetes objects are like instructions that tell your Kubernetes cluster how to run your applications.

## Architecture:
`Master Node:` Controls the Kubernetes cluster, including scheduling, deploying applications, and managing nodes.

`Worker Node:` Executes the tasks assigned by the Master Node, running Pods and providing the Kubernetes runtime environment.

## Control Plane Components:
`API Server:` Exposes the Kubernetes API, which the other components interact with to manage the cluster.

`Scheduler:` Assigns Pods to nodes based on resource requirements and availability.

`Controller Manager:` Watches the state of the cluster and makes changes to move the current state towards the desired state.

`etcd:` A distributed key-value store that stores the cluster's configuration data.

## Deployment:
Define application deployment configurations using YAML manifests (`Declarative approach`) or use commands on the go (`Imperative approach`).
Deployments ensure the desired state by managing replica sets, which maintain a stable set of replica Pods.
Rolling updates and rollback capabilities are built-in, allowing for seamless updates and recovery.

## Typical Flow
- 1: Install Kubernetes
- 2: Ensure `Kubectl` is working (kubectl is the component that talks to API Server in order to create cluster).
- 3: To create a deployment declaratively, write a manifest `(yml, yaml, or Json)` file.
- 4: Run kubectl apply <manifestfilename>.

### Scaling:
`Horizontal Pod Autoscaler (HPA)` automatically adjusts the number of Pods in a deployment based on CPU or custom metrics.

`Cluster Autoscaler adjusts` the number of nodes in a cluster based on resource demand.

## Networking:
Kubernetes assigns each Pod a `unique IP address` (remember, pod, not a container, the pod can consist of one or more containers, this can be a tricky question during the interview, as the container does not get its own IP address), allowing Pods to communicate with each other.

`Services` provide stable endpoints for Pods, abstracting away individual Pod IP addresses.

`Container Network Interface (CNI)` plugins enable networking solutions such as overlay networks, enabling communication across nodes.

## Storage:
`PersistentVolume (PV) and PersistentVolumeClaim (PVC)` resources provide storage solutions for Pods that require data persistence.

`StorageClasses` allow dynamic provisioning of storage volumes based on storage requirements specified by PVCs.

## Security:
`Role-Based Access Control (RBAC)` restricts access to Kubernetes resources based on roles and permissions.

`Pod Security Policies (PSP)` enforce security policies at the Pod level, controlling actions like privilege escalation and volume mounting.

`Network Policies` define how Pods can communicate with each other and other network endpoints.

## Monitoring and Logging:
Kubernetes integrates with monitoring and logging solutions like `Prometheus`, `Grafana`, and `ELK stack` for monitoring cluster health, resource usage, and application logs.

`Metrics Server` provides resource utilization metrics for Pods and nodes.

## Resource Management:
Kubernetes allows resource requests and limits to be set for Pods, ensuring fair resource allocation and preventing resource starvation.

`Quality of Service (QoS)` classes classify Pods into three categories (Guaranteed, Burstable, BestEffort) based on their resource requirements and limits.

## High Availability:
Kubernetes supports multi-master configurations and automatic failover to ensure high availability of the control plane.
Application workloads can be distributed across multiple nodes to prevent single points of failure.

## Extensibility:
Custom Resource Definitions (CRDs) and Custom Controllers are used to enhance the functionality of Kubernetes.

## Minikube
Simplest utility that fires up a single node Kubernetes cluster on any machine.
