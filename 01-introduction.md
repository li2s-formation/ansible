---
transition: fade-out
---

# Table des matières

- Introduction
- Installation
- Configuration
- Les Pods
- Le Scheduler
- Les Services
- Les deploiements
- Les Namespace
<br>
<br>


---
transition: slide-left
---

<br>
<br>
<center>
<img src="/intro.png" width="400" height="500">
</center>


---
transition: fade-out
---

# Historique

- Kubernetes ou k8s
- Borg de Google
- Cloud Native Computing Foundation (CNCF)
- Version 1.0 07/2015
- Version 1.35 12/2025
<br>
<br>

---
transition: fade-out
---

# Qu’est ce que Kubernetes

- Orchestrateur
- Gestion d’applications conteneurisées
  - Déploiment
  - Self-healing
  - Montée en charge
  - Mise à jour
- Gestion des configurations
- Gestion des mots de passes (Secrets)
- RBAC
<br>
<br>

---
transition: fade-out
---

# Concepts de base / Cluster

<br>
 
## Cluster Kubernetes

- Ensemble de Nodes
- Linux ou Windows(1.14)
<br>
<br>
<br>
<br>
<br>
<center>
<img src="/intro.png">
</center>

---
transition: fade-out
---

# Concepts de base / Pods

<br>
 
## Pods

<div class="grid grid-cols-2">
<div>
<ul style="list-style-type:square;">
  <li>Ensemble de conteneurs</li>
  <li>Partage Réseau</li>
  <li>Partage Stockage</li>
</ul>

</div>
<div v-click="4">

```yaml [pod.yml]      
kind: Pod
spec:
  containers:
  - name: web
```
</div>
</div>






<br>
<br>
<center>
<img src="/intro.png">
</center>


