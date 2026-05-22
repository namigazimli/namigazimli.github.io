---
layout: default
title: Namig Azimli - Senior DevOps Engineer
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap');

  /* Hide default GitHub Pages theme headers to prevent duplication */
  header, .site-header, .page-header, #header { display: none !important; }
  h1 { display: none !important; }

  :root {
    --bg-color: #fafafa;
    --text-main: #333333;
    --text-muted: #666666;
    --accent: #0070f3;
    --border-color: #eaeaea;
    --pill-bg: #e5e7eb;
    --pill-hover: #d1d5db;
  }

  @media (prefers-color-scheme: dark) {
    :root {
      --bg-color: #0d1117;
      --text-main: #c9d1d9;
      --text-muted: #8b949e;
      --accent: #58a6ff;
      --border-color: #30363d;
      --pill-bg: #21262d;
      --pill-hover: #30363d;
    }
  }

  body {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    line-height: 1.6;
    color: var(--text-main);
    background-color: var(--bg-color);
    max-width: 850px;
    margin: 0 auto;
    padding: 60px 20px;
    -webkit-font-smoothing: antialiased;
  }

  h2 { 
    font-size: 1.5em; 
    margin-top: 2em; 
    padding-bottom: 0.4em; 
    border-bottom: 1px solid var(--border-color); 
    color: var(--text-main);
    font-weight: 700;
    letter-spacing: -0.02em;
  }
  
  h3 { 
    font-size: 1.2em; 
    margin-top: 1.5em; 
    margin-bottom: 0.2em; 
    color: var(--text-main);
    font-weight: 600;
  }
  
  p, li { color: var(--text-muted); }
  strong { color: var(--text-main); font-weight: 600; }
  a { color: var(--accent); text-decoration: none; transition: all 0.2s ease; }
  a:hover { text-decoration: underline; }

  /* Modern Profile Header */
  .profile-header {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    margin-bottom: 3rem;
    padding-bottom: 3rem;
    border-bottom: 1px solid var(--border-color);
  }

  @media (min-width: 600px) {
    .profile-header {
      flex-direction: row;
      text-align: left;
      gap: 2rem;
    }
  }

  .avatar {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid var(--border-color);
    box-shadow: 0 8px 20px rgba(0,0,0,0.1);
    margin-bottom: 1.5rem;
  }

  @media (min-width: 600px) {
    .avatar { margin-bottom: 0; width: 160px; height: 160px; }
  }

  .name-heading {
    font-size: 2.8rem;
    font-weight: 800;
    margin: 0 0 0.2rem 0;
    letter-spacing: -0.04em;
    background: linear-gradient(90deg, #58a6ff, #00dfd8);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }

  .title {
    font-size: 1.2rem;
    font-weight: 500;
    color: var(--text-main);
    margin: 0 0 0.5rem 0;
  }

  .location {
    font-size: 0.95rem;
    color: var(--text-muted);
    margin: 0 0 1.2rem 0;
  }

  /* Pill Buttons */
  .social-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
    justify-content: center;
  }

  @media (min-width: 600px) {
    .social-links { justify-content: flex-start; }
  }

  .social-links a {
    display: inline-flex;
    align-items: center;
    padding: 0.4rem 1rem;
    background-color: var(--pill-bg);
    color: var(--text-main);
    border-radius: 9999px;
    font-size: 0.9rem;
    font-weight: 500;
  }

  .social-links a:hover {
    background-color: var(--pill-hover);
    text-decoration: none;
    transform: translateY(-1px);
  }

  ul { padding-left: 1.2rem; margin-top: 0.5rem; }
  li { margin-bottom: 0.4rem; }

  /* Fallback for Jekyll Tables */
  table, th, td, tr { background-color: transparent !important; border-color: var(--border-color) !important; color: var(--text-main) !important; }

  /* Print Optimization */
  @media print {
    body { padding: 0; background: white; max-width: 100%; color: black; }
    .profile-header { border-bottom: none; padding-bottom: 1rem; margin-bottom: 1rem; }
    .name-heading { background: none; -webkit-text-fill-color: black; color: black; }
    .social-links a { border: 1px solid black; background: white; color: black; }
    @page { margin: 0.5in; }
  }
</style>

<div class="profile-header">
  <img src="https://github.com/namigazimli.png" alt="Namig Azimli" class="avatar">
  
  <div class="profile-info">
    <div class="name-heading">Namig Azimli</div>
    <p class="title">Senior DevOps & SRE Engineer</p>
    <p class="location">📍 Baku, Azerbaijan</p>
    
    <div class="social-links">
      <a href="mailto:namiqazimli28@gmail.com">Email</a>
      <a href="https://www.linkedin.com/in/namig-azimli/" target="_blank">LinkedIn</a>
      <a href="https://www.credly.com/users/namig-azimli" target="_blank">Credly</a>
    </div>
  </div>
</div>

## Professional Summary
[cite_start]Innovative Senior DevOps Engineer with over three years of dedicated experience building secure, highly observable cloud-native platforms. [cite: 5] [cite_start]I specialise in advanced GitOps implementations, specifically decoupling application and infrastructure repositories using Kustomize, Helm, FluxCD, and ArgoCD. [cite: 6] [cite_start]With a strong focus on "shift-left" security practices (Vault, Trivy, SonarQube) and building resilient, highly observable microservice architectures, I design solutions that bridge the gap between complex infrastructure and developer productivity. [cite: 7]

## Core Technical Skills
* [cite_start]**Cloud & Orchestration:** Kubernetes, OpenShift, Google Cloud Platform (GCP). [cite: 47]
* [cite_start]**GitOps & CI/CD:** ArgoCD, FluxCD, Helm, Kustomize, GitLab CI, BuildKit. [cite: 48, 52]
* [cite_start]**Networking & Service Mesh:** Istio, Cilium, NGINX. [cite: 49, 50]
* [cite_start]**Security & Policy:** HashiCorp Vault, Bitnami Sealed Secrets, Kyverno, Trivy, SonarQube. [cite: 51]
* [cite_start]**Observability:** OpenTelemetry, Prometheus, Grafana, Zabbix, PRTG Monitor. [cite: 54]
* [cite_start]**Scripting & Languages:** Python, Go (Golang), Bash. [cite: 53]
* [cite_start]**Systems Administration:** Linux System Administration (RHCE/RHCSA). [cite: 55]

## Featured Engineering Projects

### Enterprise OpenShift Migration & LDAP Integration
* Successfully executed the migration of OpenShift cluster virtual machines between Nutanix environments to ensure optimal resource allocation and high availability.
* Implemented full OpenShift LDAP integration, synchronizing cluster-administrator groups to establish streamlined and secure role-based access control (RBAC).

### AI-Driven Merge Request Automation
* Developed and integrated an AI-driven Merge Request (MR) reviewer repository directly into GitLab CI/CD workflows.
* Automated the analysis of codebase changes, generating detailed markdown feedback and appending descriptions directly into MRs to accelerate peer reviews and maintain code quality.

### GitOps Transformation & Secrets Management
* [cite_start]Architected a complete GitOps workflow, designating Git repositories as the single source of truth for both infrastructure and application configurations. [cite: 16]
* Hardened complex microservice environments by integrating HashiCorp Vault and transitioning plain text secrets to Bitnami Sealed Secrets for secure reconciliation.
* Scaled production microservices utilizing HorizontalPodAutoscalers (HPA) and PodDisruptionBudgets (PDB) via Kustomize patches for zero-downtime deployments.

### Disaster Recovery & Automated Resilience
* Engineered automated network recovery shell scripts designed for seamless Linux VM backup and restore processes across geographically separated data centers.
* Established robust daily cron backups of critical production data directly to MinIO buckets, ensuring persistent data reliability and rapid disaster recovery capabilities.

## Professional Experience

### Senior DevOps Engineer
**Central Bank of the Republic of Azerbaijan** &bull; [cite_start]*Apr 2025 - Present* [cite: 9, 10]
* [cite_start]Lead the design, implementation, and continuous improvement of automation frameworks across the software development lifecycle (SDLC). [cite: 11]
* [cite_start]Proactively identify bottlenecks and drive optimisation initiatives to enhance system performance and developer productivity. [cite: 12]
* [cite_start]Architect, build, and manage sophisticated CI/CD pipelines for complex microservice environments. [cite: 13]
* [cite_start]Ensure pipelines are secure, fast, and reliable, incorporating best practices for automated testing and progressive delivery. [cite: 14]
* [cite_start]Design and implement comprehensive monitoring, logging, and alerting strategies (observability) for distributed systems and microservice architectures. [cite: 15]

### DevOps Engineer
**BestComp Group** &bull; [cite_start]*Jan 2024 - Apr 2025* [cite: 17, 18]
* [cite_start]Administered and maintained production-grade Kubernetes clusters, managing the full lifecycle from cluster provisioning and node pool scaling to version upgrades. [cite: 19]
* [cite_start]Secured cluster environments by implementing fine-grained RBAC, Network Policies to enforce workload isolation and the principle of least privilege. [cite: 20]
* [cite_start]Engineered cluster-wide services, including Ingress controllers (NGINX), persistent storage (PV/PVCs), and service mesh (Istio) to support developer applications. [cite: 21]
* [cite_start]Managed application delivery using ArgoCD, configuring it to automatically sync and reconcile the cluster's live state with the desired state defined in Git. [cite: 22]
* [cite_start]Developed and managed reusable Helm charts to standardise application deployments, managing chart lifecycles and application configurations across development, staging, and production environments. [cite: 23]

### DevOps Engineer
**A2Z Technologies** &bull; [cite_start]*Mar 2022 - Jan 2024* [cite: 24, 25]
* [cite_start]Work collaboratively with software engineers, architects, and quality assurance to deploy and operate the systems. [cite: 26]
* [cite_start]Performing general technical troubleshooting & giving consultation to development teams. [cite: 27]
* [cite_start]Troubleshoot and resolve issues in development, test, and production environments. [cite: 27]

### Senior OSS Operations Engineer
**Azerconnect Group** &bull; [cite_start]*July 2021 - Mar 2022* [cite: 28, 29]
* [cite_start]Maintains smooth operation and administration of OSS systems, including coordination with network engineers. [cite: 30]
* [cite_start]Manage the complex OSS system and related tools, planned works and work orders implementation. [cite: 31]
* [cite_start]Provide support to the other units in case of faults and problems in the functionality of the OSS/EMS systems. [cite: 32]

### Junior Linux Administrator
**Ministry of Internal Affairs** &bull; [cite_start]*Sep 2020 - July 2021* [cite: 33, 34]
* [cite_start]Orchestrated the end-to-end configuration, deployment, and hardening of bare-metal Linux servers (RHEL, CentOS) in high-availability production environments. [cite: 35]
* [cite_start]Engineered and maintained comprehensive infrastructure monitoring solutions using Zabbix and PRTG Monitor to ensure 24/7 visibility across servers, network, and storage. [cite: 36]
* [cite_start]Authored and maintained custom Bash shell scripts to automate complex system administration tasks, reducing manual error and improving operational efficiency. [cite: 37]

### IT Engineer
**SINAM** &bull; [cite_start]*June 2019 - Sep 2020* [cite: 38, 39]
* [cite_start]Managed the full hardware lifecycle, including the deployment, configuration, and setup of new workstations/peripherals and the decommissioning/replacement of faulty or end-of-life equipment. [cite: 40]
* [cite_start]Administered system updates and patch management for operating systems and drivers to ensure security compliance, system stability, and optimal performance. [cite: 41]

## Education
* **Bachelor of Computer Science** &bull; [cite_start]*Baku State University* (Sep 2012 - June 2016) [cite: 43, 44, 45]

## Certifications
* **Google Cloud Professional Cloud DevOps Engineer**
* **CNCF Golden Kubestronaut**
