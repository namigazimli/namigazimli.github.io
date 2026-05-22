---
layout: default
title: Namig Azimli - Senior DevOps Engineer
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap');

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

  table, th, td, tr { background-color: transparent !important; border-color: var(--border-color) !important; color: var(--text-main) !important; }

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
Innovative Senior DevOps Engineer with over three years of experience building secure, highly observable cloud‑native platforms. I specialise in advanced GitOps implementations using Kustomize, Helm, FluxCD, and ArgoCD. With a strong focus on shift‑left security and resilient microservice architectures, I design solutions that bridge complex infrastructure with developer productivity.

## Core Technical Skills
- **Cloud & Orchestration:** Kubernetes, OpenShift, Google Cloud Platform (GCP)
- **GitOps & CI/CD:** ArgoCD, FluxCD, Helm, Kustomize, GitLab CI, BuildKit
- **Networking & Service Mesh:** Istio, Cilium, NGINX
- **Security & Policy:** HashiCorp Vault, Bitnami Sealed Secrets, Kyverno, Trivy, SonarQube
- **Observability:** OpenTelemetry, Prometheus, Grafana, Zabbix, PRTG Monitor
- **Scripting & Languages:** Python, Go (Golang), Bash
- **Systems Administration:** Linux System Administration (RHCE/RHCSA)

## Featured Engineering Projects

### Enterprise OpenShift Migration & LDAP Integration
- Executed migration of OpenShift cluster virtual machines between Nutanix environments to improve resource allocation and availability.
- Implemented OpenShift LDAP integration and synchronized cluster-administrator groups for secure RBAC.

### AI-Driven Merge Request Automation
- Developed an AI-driven Merge Request reviewer integrated into GitLab CI/CD to automate code analysis and append markdown feedback to MRs.

### GitOps Transformation & Secrets Management
- Architected a GitOps workflow with Git as the single source of truth for infrastructure and application configurations.
- Hardened microservice environments by integrating HashiCorp Vault and migrating plaintext secrets to Sealed Secrets.
- Scaled production microservices using HPA and PDB via Kustomize patches for zero-downtime deployments.

### Disaster Recovery & Automated Resilience
- Built automated network recovery scripts for Linux VM backup/restore across geographically separated data centers.
- Implemented daily cron backups of production data to MinIO for reliable disaster recovery.

## Professional Experience

### Senior DevOps Engineer
**Central Bank of the Republic of Azerbaijan** • Apr 2025 - Present
- Lead design and continuous improvement of automation frameworks across the SDLC.
- Identify bottlenecks and drive optimisation to improve system performance and developer productivity.
- Architect, build, and manage CI/CD pipelines for complex microservice environments.
- Implement monitoring, logging, and alerting strategies for distributed systems.

### DevOps Engineer
**BestComp Group** • Jan 2024 - Apr 2025
- Administered production-grade Kubernetes clusters; handled provisioning, scaling, and upgrades.
- Implemented RBAC and Network Policies to enforce workload isolation.
- Managed Ingress (NGINX), persistent storage (PV/PVC), and Istio service mesh.
- Used ArgoCD for GitOps-based application delivery and maintained reusable Helm charts.

### DevOps Engineer
**A2Z Technologies** • Mar 2022 - Jan 2024
- Collaborated with engineering teams to deploy and operate systems.
- Performed technical troubleshooting and provided consultation to development teams.

### Senior OSS Operations Engineer
**Azerconnect Group** • Jul 2021 - Mar 2022
- Maintained OSS systems and coordinated with network engineering teams.
- Managed OSS tools, planned work orders, and supported fault resolution.

### Junior Linux Administrator
**Ministry of Internal Affairs** • Sep 2020 - Jul 2021
- Configured, deployed, and hardened bare-metal Linux servers (RHEL, CentOS).
- Implemented monitoring with Zabbix and PRTG; authored Bash automation scripts.

### IT Engineer
**SINAM** • Jun 2019 - Sep 2020
- Managed hardware lifecycle and workstation deployments.
- Administered system updates and patch management.

## Education
- **Bachelor of Computer Science** — Baku State University (Sep 2012 - Jun 2016)

## Certifications
- **Google Cloud Professional Cloud DevOps Engineer**
- **CNCF Golden Kubestronaut**
