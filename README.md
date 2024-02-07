Kubermeta
=========

El objetivo de este repositorio es el de recopilar información relativa a Kubernetes. La idea es abarcar:
- Contenido teorico y certificaciones.
- Contenido práctico (creación de clusters usando vagrant)

# CKA Learning Path
La certificación [_Certified Kubernetes Administrator (CKA)_](https://training.linuxfoundation.org/certification/certified-kubernetes-administrator-cka/)
 es la certificación básica sobre Kubernetes. 
 La propia fundación linux propone estos cursos gratuitos:
- [_Introduction to
Kubernetes (LFS158x)_](https://training.linuxfoundation.org/training/introduction-to-kubernetes/)
- [_Introduction to Cloud Infrastructure
Technologies (LFS151x)_](https://training.linuxfoundation.org/training/introduction-to-cloud-infrastructure-technologies/)

Y estos cursos de pago:
- [_Containers Fundamentals (LFS253_)](https://training.linuxfoundation.org/training/containers-fundamentals/)
- [_Kubernetes Fundamentals (LFS258)_](https://training.linuxfoundation.org/training/kubernetes-fundamentals/)

Los conceptos que abarca la certificación son los siguientes:
- Storage (10%)
  - Understand storage classes, persistent volumes
  - Understand volume mode, access modes and reclaim policies for volumes
  - Understand persistent volume claims primitive
  - Know how to configure applications with persistent storage

- Troubleshooting (30%)
  - Evaluate cluster and node logging
  - Understand how to monitor applications
  - Manage container stdout & stderr logs
  - Troubleshoot application failure
  - Troubleshoot cluster component failure
  - Troubleshoot networking

- Workloads & Scheduling (15%)
  - Understand deployments and how to perform rolling update and rollbacks
  - Use ConfigMaps and Secrets to configure applications
  - Know how to scale applications
  - Understand the primitives used to create robust, self-healing, application deployments
  - Understand how resource limits can affect Pod scheduling
  - Awareness of manifest management and common templating tools

- Cluster Architecture, Installation & Configuration (25%)
  - Manage role based access control (RBAC)
  - Use Kubeadm to install a basic cluster
  - Manage a highly-available Kubernetes cluster
  - Provision underlying infrastructure to deploy a Kubernetes cluster
  - Perform a version upgrade on a Kubernetes cluster using Kubeadm
  - Implement etcd backup and restore

- Services & Networking (20%)
  - Understand host networking configuration on the cluster nodes
  - Understand connectivity between Pods
  - Understand ClusterIP, NodePort, LoadBalancer service types and endpoints
  - Know how to use Ingress controllers and Ingress resources
  - Know how to configure and use CoreDNS
  - Choose an appropriate container network interface plugin

  Dichos conceptos se abarcan en [LFS158x.md](https://github.com/vgenguita/kubermeta/blob/main/LFS158x.md) y [CKA.md]()