# Kubernetes Template
This template contains the following configurations:

## APIS

### dashboards
  - "dashboard/\U0001F578 Kubernetes Overview - Performance Enginnering"
  - "dashboard/\U0001F578 Kubernetes Overview - Container usage & health"
  - "dashboard/\U0001F578 Kubernetes Overview - Cluster Utilization"
  - "dashboard/\U0001F578 Kubernetes Overview - User Experience"
  - "dashboard/\U0001F578 Kubernetes Overview - Resource Quotas"
  - "dashboard/\U0001F578 Kubernetes Overview"
  - "dashboard/Simplify Kubernetes Complexity with Advanced AI Ops"
  - "dashboard/Kubernetes Metric Expressions"

### conditional-naming-service
  - "conditional-naming-service/K8s Service Naming Convention"
```json
{Service:DetectedName}.svc.{ProcessGroup:KubernetesContainerName}.{ProcessGroup:KubernetesNamespace}
```


### conditional-naming-processgroup
  - "conditional-naming-processgroup/K8s PG Naming Convention"
```json
{ProcessGroup:ExeName}.{ProcessGroup:KubernetesContainerName}.{ProcessGroup:KubernetesNamespace}.{KubernetesCluster:Name}
```

### auto-tag
  - "auto-tag/[Kubernetes]namespace"

-----
## 📊 Dashboards 

### Kubernetes Overview
![#](../doc/kubernetes/overview.png)


### Cluster utilization
_____________________
See the Kubernetes cluster utilization. CPU and Memory Request and limits over time for all nodes and splitted by namespaces.
![#](../doc/kubernetes/cluster-utilization.png)


### Resource Quotas
_____________________
Get an overview and understanding of the Kubernetes resource quotas (Memory and CPU) assigned to your namespaces and its usage. 
![#](../doc/kubernetes/quotas.png)

### Container usage & health
_____________________
Understand the health and phases of your Pods in your clusters. Their memory and cpu usage, which pods are throttled, have failed or are pending to be scheduled. Also check if you have Out-of-memory killed containers.

![#](../doc/kubernetes/containers.png)

### Performance Engineering
_____________________
Give your developers and SRE engineers all they need to understand and improve the performance of each app, pod and each transaction on your clusters. View the response time percentiles, slow transactions, database executions per microservice, its network usage and more. Filter the transactions by App label, namespace and much more.  

![#](../doc/kubernetes/performanceeng.png)

### User Experience
_____________________
Are your endusers satisfied? how is the engagement, experience and user behaviour of your applications? Get the insights of all your applications and users in an instance.

![#](../doc/kubernetes/userexperience.png)