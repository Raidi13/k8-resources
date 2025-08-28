# Kubernetes YAML Examples

This repository contains a collection of **Kubernetes YAML manifest files** that illustrate different Kubernetes resources and configurations. It is designed as a reference and learning resource for understanding how Kubernetes objects are defined and deployed.

## 📂 Contents

- **01-namespace.yaml** → Defines a custom namespace.

- **02-pod.yaml** → Basic Pod definition.

- **03-multi-container.yaml** → Pod with multiple containers.

- **04-labels.yaml** → Using labels for organizing resources.

- **05-annotations.yaml** → Adding metadata with annotations.

- **06-env.yaml** → Environment variables in Pods.

- **07-resource-limits.yaml** → CPU & memory limits.

- **08-config-map.yaml** → Storing configuration data.

- **09-pod-config.yaml** → Pod consuming a ConfigMap.

- **10-secret.yaml** → Secret definition.

- **11-pod-secret.yaml** → Pod consuming a Secret.

- **12-service.yaml** → Exposing Pods with a Service.

- **13-node-port.yaml** → Service of type NodePort.

- **14-load-balancer.yaml** → Service of type LoadBalancer.

- **15-replica-set.yaml** → ReplicaSet for scaling Pods.

- **16-deployment.yaml** → Deployment with rolling updates.

- **17-daemonset.yaml** → Running Pods on all nodes.

- **18-service-account.yaml** → Custom ServiceAccount.

## 🚀 Usage

Apply any YAML file to your Kubernetes cluster:


kubectl apply -f <file-name>.yaml


kubectl get all
