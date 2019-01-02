# cka-ckad-prep
prep notes for cka and ckad

Based on: current version of Kubernetes:  1.11.1 

## Keystrokes to use:
* For Mac: ⌘+C to copy and ⌘+V to paste.
* Use Ctrl+Alt+W instead of Ctrl+W. Ctrl+W is a keyboard shortcut that will close the current tab in Google Chrome
* tmux
* Ref websites allowed:

	 ​https://kubernetes.io/docs/​  
	 https://kubernetes.io/blog/​ 
	 -- do not go to any other external sites!!!


## Helpful links:
* [dstorck's cka-prep materials](https://github.com/DStorck/cka-prep)
* [matthewpalmer's Kubernetes for Application Developers
](https://matthewpalmer.net/kubernetes-app-developer/)
* [dgkanatsios' ckad prep materials](https://github.com/dgkanatsios/CKAD-exercises)
* [saripurigopi's ckad prep materials](https://github.com/saripurigopi/CKAD)
* [twajr's ckad prep materials](https://github.com/twajr/ckad-prep-notes)
* [kelsey hightower's kubernetes the hardway](https://github.com/kelseyhightower/kubernetes-the-hard-way)

## Other Study Materials:
* Linux Academy - Kubernetes the Hard Way
* Linux Acamemy - Certified Kubernetes Administrator
* Udemy - Loony Corn - Kubernetes On the Cloud and the CNCF CKA Certification
* CNCF - Training Materials 
 

# CKA

Core Concepts - 19%
- [ ] Understand the Kubernetes API primitives.
- [ ] Understand the Kubernetes cluster architecture.
- [ ] Understand Services and other network primitives.

Installation, Configuration & Validation - 12%
- [ ] Design a Kubernetes cluster.
- [ ] Install Kubernetes masters and nodes.
- [ ] Configure secure cluster communications.
- [ ] Configure a Highly-Available Kubernetes cluster.
- [ ] Know where to get the Kubernetes release binaries.
- [ ] Provision underlying infrastructure to deploy a Kubernetes cluster.
- [ ] Choose a network solution.
- [ ] Choose your Kubernetes infrastructure configuration.
- [ ] Run end-to-end tests on your cluster. Analyse end-to-end tests results. Run Node end-to-end tests.

Cluster Maintenance - 11%
- [ ] Understand Kubernetes cluster upgrade process.
- [ ] Facilitate operating system upgrades.
- [ ] Implement backup and restore methodologies.

Networking - 11%
- [ ] Understand the networking configuration on the cluster nodes.
- [ ] Understand Pod networking concepts.
- [ ] Understand service networking.
- [ ] Deploy and configure network load balancer.
- [ ] Know how to use Ingress rules.
- [ ] Know how to configure and use the cluster DNS.
- [ ] Understand CNI.

Scheduling - 5%
- [ ] Use label selectors to schedule Pods. 
- [ ] Understand the role of DaemonSets.
- [ ] Understand how resource limits can affect Pod scheduling.
- [ ] Understand how to run multiple schedulers and how to configure Pods to use them.
- [ ] Manually schedule a pod without a scheduler.
- [ ] Display scheduler events.
- [ ] Know how to configure the Kubernetes scheduler.

Security - 12%
- [ ] Know how to configure authentication
      and authorization.
- [ ] Understand Kubernetes security primitives.
- [ ] Know to configure network policies.
- [ ] Create and manage TLS certificates for
- [ ] cluster components.
- [ ] Work with images securely.
- [ ] Define security contexts.
- [ ] Secure persistent key value store.

Storage - 7%
- [ ] Understand persistent volumes and know how to create them.
- [ ] Understand access modes for volumes.
- [ ] Understand persistent volume claims primitive.
- [ ] Understand Kubernetes storage objects.
- [ ] Know how to configure applications with persistent storage.

Application Lifecycle Management - 8%
- [ ] Understand Deployments and how to perform rolling updates and rollbacks.
- [ ] Know various ways to configure applications. Know how to scale applications.
- [ ] Understand the primitives necessary to create a self-healing application.

Logging/Monitoring - 5%
- [ ] Understand how to monitor all cluster components.
- [ ] Understand how to monitor applications. • Manage cluster component logs.
- [ ] Manage application logs.

Troubleshooting - 10%
- [ ] Troubleshoot application failure.
- [ ] Troubleshoot control plane failure.
- [ ] Troubleshoot worker node failure.
- [ ] Troubleshoot networking.


# CKAD

Core Concepts - 13%
- [ ] Understand Kubernetes API primitives 
- [ ] Create and configure basic Pods

10% Multi-Container Pods
- [ ] Understand Multi-Container Pod design patterns (e.g. ambassador, adapter, sidecare)

Pod Design - 20%
- [ ] Understand how to use Labels, Selectors, and Annotations
- [ ] Understand Deployments and how to perform rolling updates
- [ ] Understand Deployments and how to perform rollbacks
- [ ] Understand Jobs and CronJobs

State Persistence - 8%
- [ ] Understand PersistentVolumeClaims for storage

Configuration - 18%
- [ ] Understand ConfigMaps
- [ ] Understand SecurityContexts
- [ ] Define an application’s resource requirements • Create & consume Secrets
- [ ] Understand ServiceAccounts

Observability - 18%
- [ ] Understand LivenessProbes and ReadinessProbes • Understand container logging
- [ ] Understand how to monitor applications in Kubernetes • Understand debugging in Kubernetes

Services & Networking - 13%
- [ ] Understand Services
- [ ] Demonstrate basic understanding of NetworkPolicies
