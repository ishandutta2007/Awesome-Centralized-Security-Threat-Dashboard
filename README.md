# Awesome-Centralized-Security-Threat-Dashboard

## Top Centralized Security & Threat Dashboard Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Unified Security Posture, Threat Detection & Compliance Visibility*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Centralized Security & Threat Dashboards**. These tools aggregate findings from multiple security sources—cloud infrastructure, endpoints, identities, and data protection systems—into a single pane of glass for risk prioritization, threat investigation, and compliance reporting.

**Examples** include Microsoft Defender for Cloud, Google Cloud Security Command Center, AWS Security Hub, Palo Alto Prisma Cloud, CrowdStrike Falcon, Datadog Security, and Wiz.

**Open-source emphasis**: This section highlights active projects for self-hosted security dashboards, cloud security posture visualization, and SIEM frontends—ideal for security engineers, SOC analysts, and organizations seeking transparent, vendor-neutral visibility without per-seat enterprise pricing.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

---

## Sector Overview & Market Dynamics

The global Cloud Security and Threat Detection market is estimated at approximately **$45B to $55B** in 2026, advancing at a compound annual growth rate (CAGR) of 13–16% driven by cloud migration, compliance mandates, and automated SecOps adoption. The sector is **moderately fragmented yet top-heavy**: while hyperscalers and platform incumbents hold significant consolidated market share through massive enterprise suites, high fragmentation persists across specialized niches (CNAPP, DSPM, identity security, and threat intelligence feeds) where fast-moving security pure-plays and open-source ecosystems continually emerge.

---

## SaaS/Hosted Platforms

The table below summarizes leading centralized security and threat dashboard platforms, sorted in descending order by company valuation/market capitalization.

| Product / Platform | Company Valuation / Revenue Size | Primary Focus & Dashboard Capabilities | Pricing (Starting Tier) | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Defender for Cloud](https://learn.microsoft.com/en-us/azure/defender-for-cloud/)** | **~$4.0T** Market Cap (Microsoft) | Unified CSPM and CWPP dashboard with Secure Score, regulatory compliance benchmarks, and attack path analysis across Azure, AWS, and GCP. | **$4.91 / server / month** (Defender for Servers Plan 1); $14.60/server/mo for Plan 2 | **30-day free trial** for workload protection plans; Foundational CSPM (Secure Score & recommendations) is **free forever**. |
| **[Google Cloud Security Command Center](https://cloud.google.com/security-command-center)** | **~$3.3T** Market Cap (Alphabet) | Centralized cloud risk management, posture evaluation, container runtime threat detection, and export pipelines into BigQuery and Pub/Sub. | **$0.0071 / vCPU-hour** (Compute Engine PAYG in Premium tier) or fixed annual spend commit | **Free forever tier** (Standard tier provides asset discovery, inventory, and basic misconfiguration detection). |
| **[AWS Security Hub](https://aws.amazon.com/security-hub/)** | **~$2.85T** Market Cap (Amazon) | Aggregates and normalizes alerts across GuardDuty, Inspector, Macie, IAM Analyzer, and partner tools into a unified console. | **$0.0010 / security check** (first 100,000 checks/account/month) | **30-day free trial** per account/Region; **Free forever tier** includes 10,000 finding ingestion events/month. |
| **[Palo Alto Prisma Cloud](https://www.paloaltonetworks.com/prisma/cloud)** | **~$230B** Market Cap (Palo Alto Networks) | Code-to-Cloud dashboard covering IaC scanning, image vulnerability registry, CIEM, and runtime host/container protection. | **~$30,000 / year** baseline contract (~100 Prisma Cloud Credits pool starting package) | **30-day free trial** (access to CSPM and CWPP evaluation features). |
| **[CrowdStrike Falcon](https://www.crowdstrike.com/)** | **~$215B** Market Cap (CrowdStrike) | Unified XDR, Next-Gen SIEM, cloud posture, and identity threat dashboard via Incident Workbench and Falcon OverWatch. | **$7.99 / device / month** ($59.99/device/year for Falcon Go; max 100 devices) | **15-day free trial** (no credit card required, full platform evaluation with 30-day money-back guarantee). |
| **[Lacework FortiCNAPP](https://www.lacework.com/)** | **~$90B** Market Cap (Fortinet) | Polygraph-driven cloud security dashboard correlating attack paths, host vulnerabilities, identity privileges, and container drift. | **$25,000 / year** (12-month starter package on AWS Marketplace; scaling at ~$250/vCPU) | **No public self-serve free tier**; 30-day sales-assisted Proof-of-Concept (PoC) evaluation upon request. |
| **[Datadog Security](https://www.datadoghq.com/)** | **~$70B** Market Cap (Datadog) | Unified observability and SecOps console integrating Cloud SIEM, CSM posture auditing, API protection, and workload runtime monitoring. | **$10.00 / host / month** (Cloud Security Management Pro, annual) or $12/host/mo on-demand | **14-day free trial** with full access to security modules; Free forever tier for basic infrastructure up to 5 hosts (1-day metrics). |
| **[Wiz](https://www.wiz.io/)** | **$32B** Valuation (Alphabet) | Graph-based multi-cloud risk visualization offering tailored Wiz Lens views across infrastructure, sensitive data, CIEM, and code pipelines. | **$24,000 / year** ($240/workload/year in 100-workload Essential packs; $38,000/yr for Advanced) | **No self-serve free tier**; 14- to 30-day sales-assisted cloud risk assessment / PoC trial on AWS Marketplace. |
| **[Druva Security Center](https://www.druva.com/)** | **$2.0B** Valuation (~$200M+ ARR) | Centralized cyber resilience posture dashboard measuring Cyber Readiness Scores, unauthorized logins, and backup environment tampering. | **$8.00 / user / month** (baseline endpoint/SaaS tier) or consumption credit model per TB-month | **30-day free trial** (up to 100 users/workload backups with full security console access). |
| **[Orca Security](https://orca.security/)** | **$1.2B** Valuation (Private Unicorn) | Agentless SideScanning dashboard delivering prioritized risk scores, cloud inventory, and compliance posture across AWS, Azure, and GCP. | **$7,000 / month** ($84,000/year Small Starter Pack on AWS Marketplace) | **30-day free trial** / complimentary cloud risk assessment. |

---

## Open-Source GitHub Projects

Curated open-source security dashboards, CSPMs, SIEMs, and threat detection platforms. Sorted in descending order by GitHub stargazers.

- **[Trivy](https://github.com/aquasecurity/trivy)** [![Stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=social&color=white)](https://github.com/aquasecurity/trivy/stargazers)  
  Comprehensive multi-target vulnerability and security scanner covering container images, file systems, Git repositories, virtual machine images, and Kubernetes configurations with built-in dashboard visualizations.
- **[Nuclei](https://github.com/projectdiscovery/nuclei)** [![Stars](https://img.shields.io/github/stars/projectdiscovery/nuclei?style=social&color=white)](https://github.com/projectdiscovery/nuclei/stargazers)  
  Fast and customizable vulnerability scanner driven by community-curated YAML templates to automate posture scanning and threat exposure analysis across web applications, networks, and cloud infrastructure.
- **[osquery](https://github.com/osquery/osquery)** [![Stars](https://img.shields.io/github/stars/osquery/osquery?style=social&color=white)](https://github.com/osquery/osquery/stargazers)  
  SQL-powered operating system instrumentation and analytics framework exposing an OS as a high-performance relational database for security investigations, compliance auditing, and host monitoring.
- **[Wazuh](https://github.com/wazuh/wazuh)** [![Stars](https://img.shields.io/github/stars/wazuh/wazuh?style=social&color=white)](https://github.com/wazuh/wazuh/stargazers)  
  Free, open-source enterprise security platform combining XDR and SIEM capabilities with centralized web dashboards for threat detection, log analysis, file integrity monitoring, and regulatory compliance.
- **[Prowler](https://github.com/prowler-cloud/prowler)** [![Stars](https://img.shields.io/github/stars/prowler-cloud/prowler?style=social&color=white)](https://github.com/prowler-cloud/prowler/stargazers)  
  Open-source Cloud Security Posture Management (CSPM) and compliance tool for AWS, Azure, GCP, and Kubernetes with HTML/JSON reports and interactive dashboard integrations mapping to CIS, NIST, ISO 27001, and HIPAA.
- **[OpenCTI](https://github.com/OpenCTI-Platform/opencti)** [![Stars](https://img.shields.io/github/stars/OpenCTI-Platform/opencti?style=social&color=white)](https://github.com/OpenCTI-Platform/opencti/stargazers)  
  Cyber Threat Intelligence (CTI) platform with modern visual threat investigation dashboards, knowledge graphs, and correlation engines structured around STIX2 and MITRE ATT&CK.
- **[Maltrail](https://github.com/stamparm/maltrail)** [![Stars](https://img.shields.io/github/stars/stamparm/maltrail?style=social&color=white)](https://github.com/stamparm/maltrail/stargazers)  
  Malicious network traffic detection system featuring real-time sensor processing and an intuitive administrative web dashboard highlighting blacklisted IP/DNS hits and threat heuristics.
- **[Graylog](https://github.com/Graylog2/graylog2-server)** [![Stars](https://img.shields.io/github/stars/Graylog2/graylog2-server?style=social&color=white)](https://github.com/Graylog2/graylog2-server/stargazers)  
  Centralized log management and SIEM platform with fast Elasticsearch/OpenSearch indexing, customizable security dashboards, and real-time alert routing.
- **[MISP](https://github.com/MISP/MISP)** [![Stars](https://img.shields.io/github/stars/MISP/MISP?style=social&color=white)](https://github.com/MISP/MISP/stargazers)  
  Open-source threat intelligence platform (sharing and collaboration) facilitating the collection, storage, visual correlation, and distribution of cyber security indicators and threat reports.
- **[Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian)** [![Stars](https://img.shields.io/github/stars/cloud-custodian/cloud-custodian?style=social&color=white)](https://github.com/cloud-custodian/cloud-custodian/stargazers)  
  Rules engine for cloud security and governance enabling real-time compliance evaluation, automated remediation, and resource metrics reporting across AWS, Azure, and GCP.
- **[DefectDojo](https://github.com/DefectDojo/django-DefectDojo)** [![Stars](https://img.shields.io/github/stars/DefectDojo/django-DefectDojo?style=social&color=white)](https://github.com/DefectDojo/django-DefectDojo/stargazers)  
  Leading open-source application security posture management (ASPM) and vulnerability correlation platform with extensive metrics dashboards, Jira integrations, and 160+ security scanner parsers.
- **[Security Onion](https://github.com/Security-Onion-Solutions/securityonion)** [![Stars](https://img.shields.io/github/stars/Security-Onion-Solutions/securityonion?style=social&color=white)](https://github.com/Security-Onion-Solutions/securityonion/stargazers)  
  Comprehensive Linux distribution and platform for threat hunting, network security monitoring, and log management with a unified SOC alert and case triage console.
- **[TheHive](https://github.com/TheHive-Project/TheHive)** [![Stars](https://img.shields.io/github/stars/TheHive-Project/TheHive?style=social&color=white)](https://github.com/TheHive-Project/TheHive/stargazers)  
  Scalable, open-source Security Incident Response Platform (SIRP) tightly integrated with MISP and Cortex for automated analyst triage and case management dashboards.
- **[XCLOAK Security Suite](https://github.com/The-Abhishek1/XCLOAK-SECURITY-SUITE)** [![Stars](https://img.shields.io/github/stars/The-Abhishek1/XCLOAK-SECURITY-SUITE?style=social&color=white)](https://github.com/The-Abhishek1/XCLOAK-SECURITY-SUITE/stargazers)  
  Open-source enterprise SOC platform combining SIEM, SOAR, EDR, DPI, MDM, and NGFW into a single self-hosted stack with autonomous Go collectors and real-time anomaly detection engines.
- **[PolySIEM](https://github.com/Realynx/PolySIEM)** [![Stars](https://img.shields.io/github/stars/Realynx/PolySIEM?style=social&color=white)](https://github.com/Realynx/PolySIEM/stargazers)  
  Self-hosted homelab SIEM with Proxmox, OPNsense, and Elastic synchronization, Suricata threat intelligence feeds, and automated host security scoring.
- **[AWS IAM Dashboard](https://github.com/AWS-IAM-Dashboard/IAM-Dashboard)** [![Stars](https://img.shields.io/github/stars/AWS-IAM-Dashboard/IAM-Dashboard?style=social&color=white)](https://github.com/AWS-IAM-Dashboard/IAM-Dashboard/stargazers)  
  Automated IAM misconfiguration detection and visualization dashboard built with OPA, Checkov, Gitleaks, Grafana, and Vite.
- **[warden](https://github.com/casareanderson/warden)** [![Stars](https://img.shields.io/github/stars/casareanderson/warden?style=social&color=white)](https://github.com/casareanderson/warden/stargazers)  
  Lightweight self-hosted security console for homelabs; inspects reverse-proxy logs, sweeps local networks, monitors container vulnerabilities, and integrates Cloudflare edge bans.
- **[AEGIS](https://github.com/Eeman1113/aegis)** [![Stars](https://img.shields.io/github/stars/Eeman1113/aegis?style=social&color=white)](https://github.com/Eeman1113/aegis/stargazers)  
  Self-hosted Streamlit dashboard connecting live AWS APIs (Security Hub, GuardDuty, IAM, Config) to visualize cloud posture and track quarterly compliance against SOC2, CIS, and NIST.
- **[Paladin Cloud (Community Edition)](https://github.com/d-demirci/PaladinCloudCE)** [![Stars](https://img.shields.io/github/stars/d-demirci/PaladinCloudCE?style=social&color=white)](https://github.com/d-demirci/PaladinCloudCE/stargazers)  
  Extensible Security-as-Code cloud security platform for multi-cloud environments providing automated asset discovery, continuous policy evaluation, and violation remediation.

---

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format and table schemas).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Security dashboards expose sensitive infrastructure and threat data; enforce strong authentication (MFA), role-based access, and audit logging on all consoles.
- Self-hosted open-source dashboards require proper hardening, credential management, and regular updates; read-only integrations should be preferred where write access is not necessary.

---

**Made for SOC analysts, security engineers, cloud architects, and organizations building unified security visibility.**  
Let's make security dashboards more open, actionable, and auditable.
