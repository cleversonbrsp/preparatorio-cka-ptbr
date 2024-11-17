Com base no detalhamento atualizado dos **Domains & Competencies**, o conteúdo abordado cobre esses tópicos com precisão. Vou mapear cada item em detrimento ao conteúdo que já expliquei, garantindo que você veja como cada área é atendida:

---

### **Storage (10%)**
1. **Understand storage classes, persistent volumes**  
   ✅ *Coberto em:* Configuração e Gerenciamento do Cluster > Storage.  
   - StorageClasses e PersistentVolumes (PVs).

2. **Understand volume mode, access modes and reclaim policies for volumes**  
   ✅ *Coberto em:* Explicação de tipos de volumes e políticas (Reclaim Policy: Retain, Recycle, Delete).

3. **Understand persistent volume claims primitive**  
   ✅ *Coberto em:* Uso de PersistentVolumeClaims (PVCs) para solicitar armazenamento.

4. **Know how to configure applications with persistent storage**  
   ✅ *Coberto em:* Exemplos de configuração de volumes para uso em Pods.

---

### **Troubleshooting (30%)**
1. **Evaluate cluster and node logging**  
   ✅ *Coberto em:* Análise de logs com `kubectl logs`, `kubectl describe` e ferramentas de monitoramento.

2. **Understand how to monitor applications**  
   ✅ *Coberto em:* Uso de probes (Liveness e Readiness) e métricas do cluster (via Metrics Server).

3. **Manage container stdout & stderr logs**  
   ✅ *Coberto em:* Comandos `kubectl logs` para analisar saída de contêineres.

4. **Troubleshoot application failure**  
   ✅ *Coberto em:* Diagnóstico de Pods (CrashLoopBackOff, Pending) e análise de descrições.

5. **Troubleshoot cluster component failure**  
   ✅ *Coberto em:* Problemas no Control Plane e nos Nodes.

6. **Troubleshoot networking**  
   ✅ *Coberto em:* Diagnóstico de conectividade entre Pods e serviços, além de Network Policies.

---

### **Workloads & Scheduling (15%)**
1. **Understand deployments and how to perform rolling update and rollbacks**  
   ✅ *Coberto em:* Gerenciamento de Deployments e uso de comandos para rollback.

2. **Use ConfigMaps and Secrets to configure applications**  
   ✅ *Coberto em:* Uso de ConfigMaps e Secrets para gerenciar variáveis e credenciais.

3. **Know how to scale applications**  
   ✅ *Coberto em:* Horizontal Pod Autoscaler (HPA) e ajustes de réplicas.

4. **Understand the primitives used to create robust, self-healing, application deployments**  
   ✅ *Coberto em:* ReplicaSets, Liveness e Readiness Probes.

5. **Understand how resource limits can affect Pod scheduling**  
   ✅ *Coberto em:* Configuração de CPU e memória (requests/limits).

6. **Awareness of manifest management and common templating tools**  
   ✅ *Coberto em:* Manifestos YAML e ferramentas como Helm (opcional, mas útil).

---

### **Cluster Architecture, Installation & Configuration (25%)**
1. **Manage role based access control (RBAC)**  
   ✅ *Coberto em:* Criação e atribuição de Roles, RoleBindings e ServiceAccounts.

2. **Use Kubeadm to install a basic cluster**  
   ✅ *Coberto em:* Instalação com `kubeadm`.

3. **Manage a highly-available Kubernetes cluster**  
   ✅ *Coberto em:* Configuração de clusters HA.

4. **Provision underlying infrastructure to deploy a Kubernetes cluster**  
   ✅ *Coberto em:* Ferramentas e recursos necessários para clusters (ex.: VMs ou cloud providers).

5. **Perform a version upgrade on a Kubernetes cluster using Kubeadm**  
   ✅ *Coberto em:* Processo de upgrade com `kubeadm upgrade`.

6. **Implement etcd backup and restore**  
   ✅ *Coberto em:* Uso do `etcdctl` para backup e restauração.

---

### **Services & Networking (20%)**
1. **Understand host networking configuration on the cluster nodes**  
   ✅ *Coberto em:* Requisitos de configuração do nó e CNI.

2. **Understand connectivity between Pods**  
   ✅ *Coberto em:* Comunicação entre Pods via DNS interno e políticas de rede.

3. **Understand ClusterIP, NodePort, LoadBalancer service types and endpoints**  
   ✅ *Coberto em:* Explicação detalhada dos tipos de Service.

4. **Know how to use Ingress controllers and Ingress resources**  
   ✅ *Coberto em:* Configuração de Ingress com hosts e paths.

5. **Know how to configure and use CoreDNS**  
   ✅ *Coberto em:* DNS interno e configurações básicas.

6. **Choose an appropriate container network interface plugin**  
   ✅ *Coberto em:* CNI como Calico, Flannel e Weave.

---

### **Conclusão**
O conteúdo que abordei cobre **integralmente** os tópicos exigidos pelo exame. Para garantir sucesso, concentre-se especialmente em **troubleshooting** (30%) e **cluster architecture** (25%), pois são os domínios mais pesados. Além disso, pratique muito em ambientes reais ou simuladores como o Killer.sh! 🚀