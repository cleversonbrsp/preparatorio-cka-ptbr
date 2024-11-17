Todos os **Domains & Competencies** especificados na documentação do exame CKA antes a sua atualização em 15/01/2025:

---

### **1. Storage (10%)**
- **Abordado em:** Configuração e Gerenciamento do Cluster > Storage.
  - PersistentVolumes (PVs) e PersistentVolumeClaims (PVCs).
  - StorageClasses.
  - Volume Mounts e Configuração de Dados.
  - Gerenciamento de armazenamento dinâmico (Dynamic Provisioning).

---

### **2. Troubleshooting (30%)**
- **Abordado em:** Troubleshooting e Monitoramento.
  - Diagnóstico e resolução de problemas em:
    - Pods (CrashLoopBackOff, Pending, etc.).
    - Nodes (Status NotReady, falhas de recursos).
    - Cluster (problemas no Control Plane, comunicação entre componentes).
  - Análise de logs com `kubectl logs` e `kubectl describe`.
  - Debug de contêineres e problemas de conectividade.
  - Uso do `etcdctl` para verificar e restaurar backups.
  - Monitoramento de métricas e comportamento do cluster.

---

### **3. Workloads & Scheduling (15%)**
- **Abordado em:** Agendamento e Escalabilidade.
  - Configuração e gerenciamento de:
    - Deployments, ReplicaSets e StatefulSets.
    - Jobs e CronJobs.
  - Controle de agendamento:
    - NodeSelector, NodeAffinity e PodAffinity.
    - Taints e Tolerations.
  - Gerenciamento de recursos:
    - Limites e requests de CPU/memória.
  - Probes:
    - Configuração de Liveness e Readiness Probes.

---

### **4. Cluster Architecture, Installation & Configuration (25%)**
- **Abordado em:** Configuração e Gerenciamento do Cluster.
  - Arquitetura do cluster:
    - Componentes do Control Plane (kube-apiserver, kube-scheduler, etcd).
    - Componentes do Node (kubelet, kube-proxy).
  - Instalação de clusters com `kubeadm`.
  - Configuração de `kubeconfig` para múltiplos clusters.
  - Atualização de clusters.
  - Configuração de alta disponibilidade (HA).
  - Configuração do runtime de contêineres.
  - Backup e restauração do etcd.

---

### **5. Services & Networking (20%)**
- **Abordado em:** Configuração e Gerenciamento do Cluster > Networking.
  - Tipos de Services:
    - ClusterIP, NodePort, LoadBalancer.
    - Configuração de ExternalName.
  - DNS interno do Kubernetes (CoreDNS).
  - Configuração e uso de Network Policies.
  - Entendimento do modelo CNI e soluções como Calico, Flannel, etc.
  - Troubleshooting de conectividade entre Pods e Nodes.

---

### **Conclusão**
Os tópicos abordados cobrem amplamente todos os domínios especificados para o exame **CKA**. Além disso, os pesos indicados (como 30% para Troubleshooting e 25% para Cluster Architecture) mostram a importância de práticas repetidas nesses domínios. Com a preparação alinhada a esta estrutura, você estará apto a cobrir todos os requisitos do exame. 🚀