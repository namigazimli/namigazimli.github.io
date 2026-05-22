---
layout: default
title: Namig Azimli - Senior DevOps Engineer
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap');

  body {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    line-height: 1.6;
    color: #333333;
    max-width: 850px;
    margin: 0 auto;
    padding: 40px 20px;
    background-color: #fcfcfc;
  }

  /* Force the main title to be a professional dark gray */
  h1 { 
    font-size: 2.5em; 
    text-align: center; 
    border-bottom: none; 
    color: #111111 !important; 
    margin-bottom: 0.2em;
  }
  
  h2 { font-size: 1.75em; border-bottom: 2px solid #eaeaea; padding-bottom: 0.3em; margin-top: 1.5em; color: #111; }
  h3 { font-size: 1.25em; margin-bottom: 0.2em; color: #111; margin-top: 1.5em; }

  a { color: #0366d6; text-decoration: none; }
  a:hover { text-decoration: underline; }

  hr {
    border: 0;
    height: 1px;
    background: #eaeaea;
    margin: 2em 0;
  }

  ul { padding-left: 20px; }
  li { margin-bottom: 0.5em; }

  .contact-info {
    text-align: center;
    font-size: 1.1em;
    color: #555;
    margin-bottom: 2em;
    line-height: 1.8;
  }

  /* Sleek Dark Mode (Auto-detects user's system preference) */
  @media (prefers-color-scheme: dark) {
    body { background-color: #0d1117; color: #c9d1d9; }
    h1, h2, h3, h4 { color: #f0f6fc !important; }
    h2 { border-bottom: 2px solid #21262d; }
    hr { background: #21262d; }
    .contact-info { color: #8b949e; }
    a { color: #58a6ff; }
  }

  /* Print Optimization (For saving as a clean PDF) */
  @media print {
    body { background-color: white; color: black; padding: 0; max-width: 100%; }
    h2 { border-bottom: 1px solid black; }
    a { text-decoration: none; color: black; }
    @page { margin: 0.75in; }
  }
</style>

<div class="contact-info">
  <strong>Senior DevOps Engineer</strong> &bull; Baku, Azerbaijan <br>
  <a href="mailto:namiqazimli28@gmail.com">namiqazimli28@gmail.com</a> &bull; 
  <a href="https://www.linkedin.com/in/namig-azimli/" target="_blank">LinkedIn</a> &bull; 
  <a href="https://www.credly.com/users/namig-azimli" target="_blank">Credly</a>
</div>

---

### Professional Summary
Innovative Senior DevOps Engineer with over three years of dedicated experience building secure, highly observable cloud-native platforms. I specialise in advanced GitOps implementations, specifically decoupling application and infrastructure repositories using Kustomize, Helm, FluxCD, and ArgoCD. With a strong focus on "shift-left" security practices (Vault, Trivy, SonarQube) and building resilient, highly observable microservice architectures, I design solutions that bridge the gap between complex infrastructure and developer productivity. 

---

### Core Technical Skills
* **Cloud & Orchestration:** Kubernetes, OpenShift, Google Cloud Platform (GCP).
* **GitOps & CI/CD:** ArgoCD, FluxCD, Helm, Kustomize, GitLab CI, BuildKit.
* **Networking & Service Mesh:** Istio, Cilium, NGINX.
* **Security & Policy:** HashiCorp Vault, Bitnami Sealed Secrets, Kyverno, Trivy, SonarQube.
* **Observability:** OpenTelemetry, Prometheus, Grafana, Zabbix, PRTG Monitor.
* **Scripting & Languages:** Python, Go (Golang), Bash.
* **Systems Administration:** Linux System Administration (RHCE/RHCSA).

---

### Featured Engineering Projects

**Enterprise OpenShift Migration & LDAP Integration**
* Successfully executed the migration of OpenShift cluster virtual machines between Nutanix environments to ensure optimal resource allocation and high availability.
* Implemented full OpenShift LDAP integration, synchronizing cluster-administrator groups to establish streamlined and secure role-based access control (RBAC).

**AI-Driven Merge Request Automation**
* Developed and integrated an AI-driven Merge Request (MR) reviewer repository directly into GitLab CI/CD workflows.
* Automated the analysis of codebase changes, generating detailed markdown feedback and appending descriptions directly into MRs to accelerate peer reviews and maintain code quality.

**GitOps Transformation & Secrets Management**
* Architected a complete GitOps workflow, designating Git repositories as the single source of truth for both infrastructure and application configurations.
* Hardened complex microservice environments by integrating HashiCorp Vault and transitioning plain text secrets to Bitnami Sealed Secrets for secure reconciliation.
* Scaled production microservices utilizing HorizontalPodAutoscalers (HPA) and PodDisruptionBudgets (PDB) via Kustomize patches for zero-downtime deployments.

**Disaster Recovery & Automated Resilience**
* Engineered automated network recovery shell scripts designed for seamless Linux VM backup and restore processes across geographically separated data centers.
* Established robust daily cron backups of critical production data directly to MinIO buckets, ensuring persistent data reliability and rapid disaster recovery capabilities.

---

### Professional Experience

**Senior DevOps Engineer** | *Central Bank of the Republic of Azerbaijan* | Apr 2025 - Present
* Lead the design, implementation, and continuous improvement of automation frameworks across the software development lifecycle (SDLC).
* Proactively identify bottlenecks and drive optimisation initiatives to enhance system performance and developer productivity.
* Architect, build, and manage sophisticated CI/CD pipelines for complex microservice environments.
* Ensure pipelines are secure, fast, and reliable, incorporating best practices for automated testing and progressive delivery.
* Design and implement comprehensive monitoring, logging, and alerting strategies (observability) for distributed systems and microservice architectures.

**DevOps Engineer** | *BestComp Group* | Jan 2024 - Apr 2025
* Administered and maintained production-grade Kubernetes clusters, managing the full lifecycle from cluster provisioning and node pool scaling to version upgrades.
* Secured cluster environments by implementing fine-grained RBAC, Network Policies to enforce workload isolation and the principle of least privilege.
* Engineered cluster-wide services, including Ingress controllers (NGINX), persistent storage (PV/PVCs), and service mesh (Istio) to support developer applications.
* Managed application delivery using ArgoCD, configuring it to automatically sync and reconcile the cluster's live state with the desired state defined in Git.
* Developed and managed reusable Helm charts to standardise application deployments, managing chart lifecycles and application configurations across development, staging, and production environments.

**DevOps Engineer** | *A2Z Technologies* | Mar 2022 - Jan 2024
* Work collaboratively with software engineers, architects, and quality assurance to deploy and operate the systems.
* Performing general technical troubleshooting & giving consultation to development teams.
* Troubleshoot and resolve issues in development, test, and production environments.

**Senior OSS Operations Engineer** | *Azerconnect Group* | July 2021 - Mar 2022
* Maintains smooth operation and administration of OSS systems, including coordination with network engineers.
* Manage the complex OSS system and related tools, planned works and work orders implementation.
* Provide support to the other units in case of faults and problems in the functionality of the OSS/EMS systems.

**Junior Linux Administrator** | *Ministry of Internal Affairs* | Sep 2020 - July 2021
* Orchestrated the end-to-end configuration, deployment, and hardening of bare-metal Linux servers (RHEL, CentOS) in high-availability production environments.
* Authored and maintained custom Bash shell scripts to automate complex system administration tasks, reducing manual error and improving operational efficiency.

**IT Engineer** | *SINAM* | June 2019 - Sep 2020
* Managed the full hardware lifecycle, including the deployment, configuration, and setup of new workstations/peripherals and the decommissioning/replacement of faulty or end-of-life equipment.
* Administered system updates and patch management for operating systems and drivers to ensure security compliance, system stability, and optimal performance.

---

### Education
* **Bachelor of Computer Science** | *Baku State University* (Sep 2012 - June 2016)

### Certifications
* **Google Cloud Professional Cloud DevOps Engineer**
* **CNCF Golden Kubestronaut**
