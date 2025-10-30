```
Cluster Setup – 
•	Use CIS benchmarks to review the security configuration of Kubernetes components (etcd, kubelet, kube-dns, kube-apiserver) 
•	Use network security policies to restrict cluster-level access 
•	Properly set up Ingress with TLS 
•	Protect node metadata and endpoints 
•	Verify platform binaries before deploying 

Cluster Hardening -
•	Use Role-Based Access Control (RBAC) to minimize exposure 
•	Exercise caution in using service accounts (e.g., disable defaults, minimize permissions on newly created ones) 
•	Restrict access to Kubernetes API 
•	Upgrade Kubernetes to avoid vulnerabilities
•	Pod-to-Pod encryption in CNI s

System Hardening – 10% 
•	Minimize host OS footprint (reduce attack surface) 
•	Use least-privilege identity and access management 
•	Minimize external access to the network 
•	Appropriately use kernel hardening tools such as AppArmor, 
•	seccomp 

Minimize Microservice Vulnerabilities – 20% 
•	Use appropriate pod security standards 
•	Manage Kubernetes secrets 

•	Understand and implement isolation techniques (e.g., multi-tenancy, sandboxed containers)
```

