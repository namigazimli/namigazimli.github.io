---
layout: default
title: Namig Azimli - Senior DevOps Engineer
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap');

  :root {
    --bg-color: #fafafa;
    --text-main: #333333;
    --text-muted: #666666;
    --accent: #0070f3;
    --border-color: #eaeaea;
    --card-bg: #ffffff;
    --pill-bg: #f3f4f6;
    --pill-hover: #e5e7eb;
  }

  @media (prefers-color-scheme: dark) {
    :root {
      --bg-color: #0a0a0a;
      --text-main: #ededed;
      --text-muted: #a1a1aa;
      --accent: #3291ff;
      --border-color: #333333;
      --card-bg: #111111;
      --pill-bg: #1f2937;
      --pill-hover: #374151;
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

  h1, h2, h3, h4 { color: var(--text-main); font-weight: 700; letter-spacing: -0.02em; }
  
  h2 { 
    font-size: 1.5em; 
    margin-top: 2em; 
    padding-bottom: 0.4em; 
    border-bottom: 1px solid var(--border-color); 
  }
  
  h3 { font-size: 1.2em; margin-top: 1.5em; margin-bottom: 0.2em; }
  
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

  .profile-info h1 {
    font-size: 2.8rem;
    font-weight: 800;
    margin: 0 0 0.2rem 0;
    letter-spacing: -0.04em;
    background: linear-gradient(90deg, #007cf0, #00dfd8);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }

  .profile-info .title {
    font-size: 1.2rem;
    font-weight: 500;
    color: var(--text-main);
    margin: 0 0 0.5rem 0;
  }

  .profile-info .location {
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
    text-decoration: none;
  }

  .social-links a:hover {
    background-color: var(--pill-hover);
    transform: translateY(-1px);
  }

  /* Timeline styling for lists */
  ul { padding-left: 1.2rem; margin-top: 0.5rem; }
  li { margin-bottom: 0.4rem; }

  /* Print Optimization */
  @media print {
    body { padding: 0; background: white; max-width: 100%; }
    .profile-header { border-bottom: none; padding-bottom: 1rem; margin-bottom: 1rem; }
    .social-links a { border: 1px solid black; }
    @page { margin: 0.5in; }
  }
</style>

<header class="profile-header">
  <img src="https://github.com/namig-azimli.png" alt="Namig Azimli" class="avatar" onerror="this.src='https://ui-avatars.com/api/?name=Namig+Azimli&size=200&background=007cf0&color=fff&font-size=0.4&bold=true'">
  
  <div class="profile-info">
    <h1>Namig Azimli</h1>
    <p class="title">Senior DevOps & SRE Engineer</p>
    <p class="location">📍 Baku, Azerbaijan</p>
    
    <div class="social-links">
      <a href="mailto:namiqazimli28@gmail.com">Email</a>
      <a href="https://www.linkedin.com/in/namig-azimli/" target="_blank">LinkedIn</a>
      <a href="https://www.credly.com/users/namig-azimli" target="_blank">Credly</a>
    </div>
  </div>
</header>

### Professional Summary
Innovative Senior DevOps Engineer with over three years of dedicated experience building secure, highly observable cloud-native platforms. I specialise in advanced GitOps implementations, specifically decoupling application and infrastructure repositories using Kustomize, Helm, FluxCD, and ArgoCD. With a strong focus on "shift-left" security practices (Vault, Trivy, SonarQube) and building resilient, highly observable microservice architectures, I design solutions that bridge the gap between complex infrastructure and developer productivity. 

## Core Technical Skills
* **Cloud & Orchestration:** Kubernetes, OpenShift, Google Cloud Platform (GCP).
* **GitOps & CI/CD:** ArgoCD, FluxCD, Helm, Kustomize, GitLab CI, BuildKit.
* **Networking & Service Mesh:** Istio, Cilium, NGINX.
* **Security & Policy:** HashiCorp Vault, Bitnami Sealed Secrets, Kyverno, Trivy, SonarQube.
* **Observability:** OpenTelemetry, Prometheus, Grafana, Zabbix, PRTG Monitor.
* **Scripting & Languages:** Python, Go (Golang), Bash.
* **Systems Administration:** Linux System Administration (RHCE/RHCSA).

## Featured Engineering Projects

### Enterprise OpenShift Migration & LDAP Integration
* Successfully executed the migration of OpenShift cluster virtual machines between Nutanix environments to ensure optimal resource allocation and high availability.
* Implemented full OpenShift LDAP integration, synchronizing cluster-administrator groups to establish streamlined and secure role-based access control (RBAC).

### AI-Driven Merge Request Automation
* Developed and integrated an AI-driven Merge Request (MR) reviewer repository directly into GitLab CI/CD workflows.
* Automated the analysis of codebase changes, generating detailed markdown feedback and appending descriptions directly into MRs to accelerate peer reviews and maintain code quality.

### GitOps Transformation & Secrets Management
* Architected a complete GitOps workflow, designating Git repositories as the single source of truth for both infrastructure and application configurations.
* Hardened complex microservice environments by integrating HashiCorp Vault and transitioning plain text secrets to Bitnami Sealed Secrets for secure reconciliation.
* Scaled production microservices utilizing HorizontalPodAutoscalers (HPA) and PodDisruptionBudgets (PDB) via Kustomize patches for zero-downtime deployments.

### Disaster Recovery & Automated Resilience
* Engineered automated network recovery shell scripts designed for seamless Linux VM backup and restore processes across geographically separated data centers.
* Established robust daily cron backups of critical production data directly to MinIO buckets, ensuring persistent data reliability and rapid disaster recovery capabilities.

## Professional Experience

### Senior DevOps Engineer
**Central Bank of the Republic of Azerbaijan** &bull; *Apr 2025 - Present*
* Lead the design, implementation, and continuous improvement of automation frameworks across the software development lifecycle (SDLC).
* Proactively identify bottlenecks and drive optimisation initiatives to enhance system performance and developer productivity.
* Architect, build, and manage sophisticated CI/CD pipelines for complex microservice environments.
* Ensure pipelines are secure, fast, and reliable, incorporating best practices for automated testing and progressive delivery.
* Design and implement comprehensive monitoring, logging, and alerting strategies (observability) for distributed systems and microservice architectures.

### DevOps Engineer
**BestComp Group** &bull; *Jan 2024 - Apr 2025*
* Administered and maintained production-grade Kubernetes clusters, managing the full lifecycle from cluster provisioning and node pool scaling to version upgrades.
* Secured cluster environments by implementing fine-grained RBAC, Network Policies to enforce workload isolation and the principle of least privilege.
* Engineered cluster-wide services, including Ingress controllers (NGINX), persistent storage (PV/PVCs), and service mesh (Istio) to support developer applications.
* Managed application delivery using ArgoCD, configuring it to automatically sync and reconcile the cluster's live state with the desired state defined in Git.
* Developed and managed reusable Helm charts to standardise application deployments, managing chart lifecycles and application configurations across development, staging, and production environments.

### DevOps Engineer
**A2Z Technologies** &bull; *Mar 2022 - Jan 2024*
* Work collaboratively with software engineers, architects, and quality assurance to deploy and operate the systems.
* Performing general technical troubleshooting & giving consultation to development teams.
* Troubleshoot and resolve issues in development, test, and production environments.

### Senior OSS Operations Engineer
**Azerconnect Group** &bull; *July 2021 - Mar 2022*
* Maintains smooth operation and administration of OSS systems, including coordination with network engineers.
* Manage the complex OSS system and related tools, planned works and work orders implementation.
* Provide support to the other units in case of faults and problems in the functionality of the OSS/EMS systems.

### Junior Linux Administrator
**Ministry of Internal Affairs** &bull; *Sep 2020 - July 2021*
* Orchestrated the end-to-end configuration, deployment, and hardening of bare-metal Linux servers (RHEL, CentOS) in high-availability production environments.
* Authored and maintained custom Bash shell scripts to automate complex system administration tasks, reducing manual error and improving operational efficiency.

### IT Engineer
**SINAM** &bull; *June 2019 - Sep 2020*
* Managed the full hardware lifecycle, including the deployment, configuration, and setup of new workstations/peripherals and the decommissioning/replacement of faulty or end-of-life equipment.
* Administered system updates and patch management for operating systems and drivers to ensure security compliance, system stability, and optimal performance.

## Education
* **Bachelor of Computer Science** &bull; *Baku State University* (Sep 2012 - June 2016)

## Certifications
* **Google Cloud Professional Cloud DevOps Engineer**
* **CNCF Golden Kubestronaut**
