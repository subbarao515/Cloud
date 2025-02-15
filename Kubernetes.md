### Kubernetes   
Kubernetes also known as K8s, is an open-source system for automating **deployment, scaling, and management of containerized applications**


### Issues and Fixes
**unable to resolve the current Docker CLI context "default": context "default": context not found**

docker context use the default 

[Ref](https://stackoverflow.com/questions/77208814/cant-log-into-minicube-message-launching-minikube-has-me-concerned-unable-to)

**error validating data: failed to download open API: Get "https://xxxx/openapi/v2?timeout=32s": dial tcp XXXX: connectex: No connection could be made because the target machine actively refused it**
minikube start

minikube service --all 

**Containers** are an application-centric method to deliver high-performing, scalable applications on any infrastructure of your choice.

**Pod** is the smallest scheduling work unit in Kubernetes

**kubelet** is an agent running on each node, control plane and workers

 **kube-proxy** is the network agent which runs on each node, control plane and workers

**Container orchestrators** are tools that group systems together to form clusters where containers' deployment and management are automated 
1. Performance.
2. Cost efficiency.
3. Workload distribution.
4. Reduced latency.

**Kubernetes Features**

  * Automatic bin packing
  * Designed for extensibility
  * Self-healing
  * Horizontal scaling
  * Service discovery and load balancing
  * Automated rollouts and rollbacks
  * Secret and configuration management
  * Storage orchestration
  * Batch execution
  * IPv4/IPv6 dual-stack

**Control Plane Node Components**
  * API Server
  * Scheduler
  * Controller Managers
  * Key-Value Data Store
    
**Worker Node Components**
  * DNS
  * Dashboard
  * Monitoring
  * Logging
  * Device plugins

**Kubernetes can be installed using different cluster configurations**
 * All-in-One Single-Node Installation
 * Single-Control Plane and Multi-Worker Installation
 * Single-Control Plane with Single-Node etcd, and Multi-Worker Installation
 * Multi-Control Plane and Multi-Worker Installation
 * Multi-Control Plane with Multi-Node etcd, and Multi-Worker Installation

**Tools**

Helm → Package manager to deploy k8s applications.

Kyverno → Policy engine to enforce security and compliance.

Kustomize → Tco customize Kubernetes configurations easily.

Kubectl → CLI to manage Kubernetes resources efficiently.

Crossplane →  k8s native tool to provision and manage cloud resources.

Karpenter → Autoscaler to optimize Kubernetes node provisioning.

Cilium → eBPF powered networking and security for Kubernetes clusters.

Velero → Backup and restore tool for Kubernetes clusters.

Falco → Security tool to detect runtime threats.
  


