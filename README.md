<div align="center">

<!-- Animated Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,12,24,30&height=220&section=header&text=Deenanath%20Yadav&fontSize=42&fontAlignY=36&animation=twinkling&desc=Senior%20DevOps%20%7C%20DevSecOps%20%7C%20Azure%20Cloud%20Architect%20%7C%20Infrastructure%20Specialist&descAlignY=58&descAlign=50" width="100%" />

<!-- Animated Live Typing Subtitle -->
<a href="https://github.com/Deenanath486">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=0078D4&background=FFFFFF00&center=true&vCenter=true&multiline=false&width=750&height=50&lines=🚀+Senior+DevOps+%26+DevSecOps+Engineer;☁️+Enterprise+Azure+Cloud+Architect;🏛️+CAF+Landing+Zones+%26+Hub-Spoke+Topology;⚙️+Production-Grade+Terraform+Automation;📦+100%2B+Workload+Migrations+%7C+FinOps+Specialist" alt="Typing Animation" />
</a>

<p align="center">
  <a href="https://www.linkedin.com/"><img src="https://img.shields.io/badge/LinkedIn-Deenanath_Yadav-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:deenanathyadav106@gmail.com"><img src="https://img.shields.io/badge/Email-deenanathyadav106%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/Deenanath486"><img src="https://img.shields.io/badge/GitHub-Deenanath486-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

<!-- Animated Core Skills Strip -->
<p align="center">
  <a href="#-comprehensive-tech-stack">
    <img src="https://skillicons.dev/icons?i=azure,terraform,kubernetes,docker,linux,bash,powershell,githubactions,python,postgres&theme=dark" alt="Skills" />
  </a>
</p>

<p align="center">
  <b>💼 7.8+ Years in IT Infrastructure</b> &nbsp;|&nbsp; 
  <b>☁️ 4.8+ Years in Azure Cloud & DevSecOps</b> &nbsp;|&nbsp; 
  <b>🚀 100+ Enterprise App Migrations</b> &nbsp;|&nbsp; 
  <b>📍 Gurugram, India</b>
</p>

> *"Designing and automating resilient cloud platforms with Infrastructure as Code, zero-downtime CI/CD pipelines, robust governance, and FinOps optimization."*

</div>

---

## 🎯 Executive Profile & Core Philosophy

Accomplished **Senior DevOps / DevSecOps Engineer & Azure Cloud Architect** with 7.8+ years of expertise in **Enterprise Cloud Infrastructure, Hands-on Modular Terraform Automation, 100+ Workload Migrations, Governance, and FinOps**.

Specialized in building platforms that are **Scalable, Robust, Secure, Portable, Governed, Highly Available, and Cost-Optimized**.

```text
┌─────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                 ENTERPRISE DELIVERY LIFECYCLE                                    │
├───────────────────┬───────────────────┬────────────────────┬────────────────────────────────────┤
│  1. ASSESS & PLAN │   2. ARCHITECT    │   3. AUTOMATE      │   4. OPERATE & GOVERN              │
│  • Discovery &    │  • CAF Framework  │  • Modular IaC     │  • FinOps & Cost Optimization      │
│    Inventory      │  • Hub-and-Spoke  │  • DevSecOps CI/CD │  • HA / BCDR (Strict RTO & RPO)    │
│  • Dependency     │  • Tenant & Entra │  • Drift Detection │  • Policy, Sentinel & Defender     │
│    Mapping        │    Hierarchy      │  • Trunk-Based Git │  • SOPs & Knowledge Transfer (KT)  │
└───────────────────┴───────────────────┴────────────────────┴────────────────────────────────────┘
```

---

## 🏛️ Comprehensive Enterprise Competencies

### 1. 🏗️ Enterprise Landing Zones & Cloud Adoption Framework (CAF)
- **CAF Lifecycle Alignment**: Designed cloud strategies covering **Strategy ➔ Plan ➔ Ready ➔ Adopt ➔ Govern ➔ Secure ➔ Manage**.
- **Tenant & Management Group Hierarchy**:
  - `Tenant Root Group` governance with isolated management partitions:
    - **Platform Management Group**: Centralized Management, Connectivity, and Identity subscriptions.
    - **Landing Zones Management Group**: Segregated subscriptions for Corp (Internal) and Online (Public-facing) workloads.
    - **Sandbox Management Group**: Guardrailed playground subscriptions with spending quotas.
    - **Decommissioned Management Group**: Orderly workload retirement and compliance archival.
- **Identity & Governance**: Microsoft Entra ID (Azure AD) enterprise group design, fine-grained **RBAC**, Azure Policy & Policy Initiatives assignment, and formal audit policy exemption workflows with business justifications.

---

### 2. 🌐 Hub-and-Spoke Networking Model & Zero-Trust Perimeter
- **IPAM & CIDR Architecture**: Comprehensive on-premises to cloud CIDR assessment, non-overlapping IP address planning, and subnet segmentation.
- **Centralized Traffic Inspection & Routing**:
  - Central Hub VNet with **Azure Firewall / NVA**, User Defined Routes (UDR `0.0.0.0/0`), and controlled egress preventing data exfiltration.
  - Spoke VNet peering with gateway transit and strict NSG boundary enforcement.
- **Private Access & Resolution**: Enterprise **Private Endpoints** for all PaaS services, centralized **Private DNS Zones** with auto-registration, and dedicated hybrid connectivity via **ExpressRoute** and **VPN Gateways**.

---

### 3. ⚙️ DevSecOps & Enterprise Terraform Automation
- **Modular IaC Framework**: Reusable Child Modules & Environment Parents (Dev, UAT, Prod) with DRY principles.
- **State File Security**: Remote state stored in encrypted Azure Storage with Customer Managed Keys (CMK), blob lease locking, private endpoints, and least-privilege RBAC.
- **Quality & Security Gates**: Pre-commit linting (`tflint`), vulnerability scanning (`tfsec` / `trivy`), secret scanning, and automated pipeline-driven **Drift Detection**.
- **Branching Governance**: Strict **Trunk-Based Branching Strategy** with short-lived feature branches, mandatory Pull Request policies, branch protections (No Delete / Force Push disabled on `main`), and mandatory Code Owners sign-off.
- **Azure DevOps Multi-Stage YAML Pipelines**:
  $$\text{Lint / Validate} \longrightarrow \text{Security Scan} \longrightarrow \text{Terraform Plan} \longrightarrow \text{Manual Approval} \longrightarrow \text{Terraform Apply} \longrightarrow \text{Rollback Drill}$$

---

### 4. 📦 Large-Scale Cloud Migration (100+ Applications)
- **Multi-Environment Delivery**: Migrated and modernized 100+ workloads across Dev, UAT, and Production across complex multi-subscription topologies from on-premises datacenters.
- **End-to-End Migration Methodology**:
  - **Discovery & Assessment**: Application dependency mapping, CMDB audits, and TCO ROI analysis.
  - **Readiness & Wave Planning**: Landing zone readiness, network latency tests, and pilot migrations.
  - **Cutover & Hypercare**: Change advisory board (CAB) sign-offs, zero-data-loss cutovers, and 24/7 post-migration hypercare support.
- **Governance & SOPs**: Standard Operating Procedures (SOPs), comprehensive pre-flight, in-flight, and post-cutover verification checklists.

---

### 5. 💰 FinOps & Continuous Cost Optimization
- **Waste Elimination**: Identification and automated remediation of idle resources, unattached managed disks, unassociated public IPs, and oversized compute instances.
- **Smart Scheduling & Rightsizing**: Automated shutdown/startup schedules for non-production environments based on business hours.
- **Capacity & Retention Strategy**: Strategic utilization of Azure Reserved VM Instances (RI), Savings Plans, Log Analytics data ingestion caps, and backup retention tuning.

---

### 6. 🛡️ BCDR, High Availability & Observability
- **High Availability (HA)**: Architected zone-redundant deployments using **Virtual Machine Scale Sets (VMSS)**, Availability Zones, and resilient storage replication (`LRS`, `ZRS`, `GRS`).
- **Disaster Recovery (DR)**: Strict **RTO (Recovery Time Objective)** and **RPO (Recovery Point Objective)** benchmarks utilizing Azure Site Recovery (ASR) across primary and secondary paired regions.
- **Observability**: Centralized monitoring with **Azure Monitor**, Log Analytics workspaces, custom metric alerts, KQL queries, and proactive operational dashboards.

---

### 7. 🤝 Technical Delivery, Operations & Transition Governance
- **Operational Excellence**: Authoring comprehensive Standard Operating Procedures (SOPs), runbooks, and disaster recovery execution plans.
- **Cross-Team Alignment**: Managing technical escalation matrices, resolving environment dependencies, and coordinating cross-functional infrastructure readiness.
- **Transitions & Knowledge Transfer**: Designing detailed RACI matrices, conducting knowledge transfer (KT) sessions, architectural documentation handover, and mentoring engineering team members.

---

## 🚀 Flagship Architecture Repositories

| Repository | Enterprise Architecture Focus | Core Technologies |
| :--- | :--- | :--- |
| 🛡️ [**Azure Bastion 3-Tier Infra**](https://github.com/Deenanath486/Azure_Bastion) | Enterprise 3-Tier Multi-VM architecture with private Bastion access, NSGs, and PostgreSQL Flexible Server with Private DNS. | `Terraform` `Azure Bastion` `PostgreSQL PaaS` `CI/CD` |
| 🌐 [**Hub-and-Spoke Network Model**](https://github.com/Deenanath486/Hub-Spoke-Model-Infra) | Scalable enterprise network topology featuring centralized hub routing, VNet peerings, controlled egress, and modular deployment. | `Azure VNet Peering` `UDR Routing` `Network Security` |
| 🏗️ [**Azure Enterprise Landing Zone**](https://github.com/Deenanath486/Landing-zone) | Production-ready Landing Zone aligned with the Microsoft Cloud Adoption Framework (CAF), Management Groups, and Azure Policies. | `Azure CAF` `Governance` `IaC` `Subscription Architecture` |
| 🔄 [**ADO Multi-Stage CI/CD Pipelines**](https://github.com/Deenanath486/ADO-Pipeline) | Production YAML templates for automated Terraform validation, environment gate approvals, drift detection, and secure execution. | `Azure DevOps` `YAML` `DevSecOps` `Branch Policies` |
| 📊 [**IP Monitoring & Observability**](https://github.com/Deenanath486/IP_Monitoring) | Network reachability health checks, IP monitoring scripts, and alerting frameworks. | `Observability` `Azure Monitor` `Automation` |

---

## 🛠️ Comprehensive Tech Stack

| Domain | Tools & Technologies |
| :--- | :--- |
| **Cloud Platforms** | Microsoft Azure (Enterprise Subscriptions, Management Groups, CAF) |
| **Infrastructure as Code** | Terraform (Parent/Child Modular, Remote State Governance), ARM, Bicep |
| **DevSecOps & CI/CD** | Azure DevOps (Pipelines, Repos, Artifacts), GitHub Actions, Git, GitOps |
| **Security & Identity** | Microsoft Entra ID (PIM, RBAC, Conditional Access), Azure Policy, Defender for Cloud, Key Vault |
| **Networking & Defense** | Azure Firewall, Azure Bastion, VNet Peering, UDRs, Private Endpoints, Private DNS, ExpressRoute, VPN |
| **Containers & K8s** | Docker, Kubernetes, Azure Kubernetes Service (AKS), Azure Container Registry (ACR) |
| **Databases & Compute** | PostgreSQL Flexible Server, Azure VMs, VM Scale Sets (VMSS), Cloud-Init, Custom Script Extension |
| **FinOps & Monitoring** | Azure Monitor, Log Analytics, Application Insights, Azure Cost Management, Advisor, KQL |
| **Scripting & OS** | Linux (Ubuntu/RHEL), Bash, PowerShell, Python, Azure CLI |

---

## 📊 GitHub Analytics & Operational Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Deenanath486&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Deenanath486&layout=compact&theme=tokyonight&hide_border=true" width="48%" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Deenanath486&theme=tokyonight&hide_border=true" width="97%" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Deenanath486&theme=tokyo-night&area=true&hide_border=true&custom_title=Enterprise%20Contributions%20%26%20Frequency" width="97%" />
</div>

---

<div align="center">

### 📬 Connect With Me
For cloud transformations, infrastructure architecture, or technical collaboration:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)
[![Email](https://img.shields.io/badge/Email-deenanathyadav106%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:deenanathyadav106@gmail.com)

*⚡ "Architecting resilient foundations, automating delivery, and securing enterprise cloud journeys." ⚡*

<!-- Animated Footer Wave -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,12,24,30&height=100&section=footer" width="100%" />

</div>
