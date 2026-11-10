# Awesome-Centralized-Security-Threat-Dashboard

# Top Centralized Security & Threat Dashboard Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Unified Security Posture, Threat Detection & Compliance Visibility*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Centralized Security & Threat Dashboards**. These tools aggregate findings from multiple security sources—cloud infrastructure, endpoints, identities, and data protection systems—into a single pane of glass for risk prioritization, threat investigation, and compliance reporting.

**Examples** include Druva Security Center, Microsoft Defender for Cloud, AWS Security Hub, Google Cloud Security Command Center, Palo Alto Prisma Cloud, Wiz, Orca Security, Lacework (FortiCNAPP), Datadog Security, and CrowdStrike Falcon (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted security dashboards, cloud security posture visualization, and SIEM frontends—ideal for security engineers, SOC analysts, and organizations seeking transparent, vendor-neutral visibility without per-seat enterprise pricing.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Druva Security Center](https://www.druva.com/)**  
  Centralized dashboard within the Druva Cloud Platform for monitoring backup environment security posture. Features a Cyber Resiliency Readiness Score tracking MFA, SSO, geofencing, restore scan, and report/alert subscriptions; Backup Risks for disconnected data sources; New Location Events for admin logins and API requests; and Access Risks for inactive or newly created administrators [citation:1]. Requires Security Posture & Observability or Accelerated Ransomware Recovery licensing.

- **[Microsoft Defender for Cloud](https://learn.microsoft.com/en-us/azure/defender-for-cloud/)**  
  Unified cloud security posture management (CSPM) and workload protection dashboard. Provides a Secure Score aggregating findings into a single risk metric, feature tiles for Security Posture, Workload Protections (CWPP), Regulatory Compliance, and Inventory, plus an Insights pane with actionable recommendations and upgrade guidance [citation:2]. Deep integration with Azure, hybrid, and multicloud resources.

- **[AWS Security Hub](https://aws.amazon.com/security-hub/)**  
  Cloud security posture management service that consolidates findings from AWS services (GuardDuty, Inspector, Macie, IAM Access Analyzer) and APN partner solutions into a standardized format. Features automated continuous checks against PCI DSS, CIS AWS Foundations, and AWS Foundational Security Best Practices; cross-Region aggregation; multi-account support via Organizations; and customizable insights for environment-specific trends [citation:3][citation:12]. Correlates related threats, vulnerabilities, and misconfigurations to surface attack paths.

- **[Google Cloud Security Command Center](https://cloud.google.com/security-command-center)**  
  Cloud risk management dashboard covering vulnerability detection (misconfigurations, exposed resources, leaked credentials), threat detection (malware, cryptomining, container runtime attacks, DDoS), security postures and policies, and compliance frameworks (NIST, HIPAA, PCI-DSS, CIS). Offers Standard, Premium, and Enterprise tiers; Enterprise requires organization-level activation. Findings can be exported to BigQuery and Pub/Sub for further analysis [citation:4].

- **[Palo Alto Prisma Cloud](https://www.paloaltonetworks.com/prisma/cloud)**  
  Code-to-Cloud dashboard providing a continuously updated snapshot of cloud security posture across Code, Build, Deploy, and Run phases. Features Cloud Inventory and Graph, Code/Build Inventory for IaC and repository scanning, Deploy Inventory for container vulnerabilities, Runtime Inventory for active incidents, and Top Issues by Collection with owner assignment [citation:5]. Compliance dashboard maps coverage to multiple standards with trend analysis.

- **[Wiz](https://www.wiz.io/)**  
  Cloud security platform with role-based Wiz Lens views tailored to different security personas. Executive Overview Lens provides CISOs with trending risks and compliance insights; Data Security Lens pinpoints sensitive data exposure; Security Development Lens tracks code-to-cloud risks for AppSec; Security Operations Lens filters active threats for SOC analysts [citation:6]. Centralized visibility with decentralized self-service execution.

- **[Orca Security](https://orca.security/)**  
  Agentless cloud security platform with an event-driven security dashboard displaying alerts by risk level, highlighting assets with suspicious activity, and providing geolocation-based insights. Unified event-driven data stream aggregates logs from all cloud service providers into a single feed; alerts organized by severity with rich contextual data to prioritize critical risks [citation:7].

- **[Lacework FortiCNAPP](https://www.lacework.com/)**  
  Cloud-native application protection platform with a configurable dashboard for monitoring risk metrics and security posture trends. Features compliance dashboard with assessability filters, Explorer for querying vulnerabilities and noncompliance with graphical network/identity relationships, and Top Work Items for attack path analysis including risky hosts, container images, exposed secrets, and admin privilege paths [citation:8][citation:19][citation:23].

- **[Datadog Security](https://www.datadoghq.com/)**  
  Security monitoring integrated into Datadog's observability platform. Cloud SIEM detects threats in real time using log management technology; Cloud Security provides continuous configuration audits and threat detection across cloud infrastructure; Workload Protection monitors file, network, and process activity; Code Security offers SAST, SCA, and secret scanning; App and API Protection detects application-level attacks . Unified with metrics, traces, and logs for full-context investigation.

- **[CrowdStrike Falcon](https://www.crowdstrike.com/)**  
  Unified security platform with centralized visibility across endpoint, identity, cloud, and SaaS domains. Features Incident Workbench for cross-domain incident mapping, Next-Gen SIEM integrating third-party telemetry, Falcon OverWatch managed threat hunting, and integrated cloud security covering infrastructure, applications, data, and AI models. Adaptive Shield acquisition adds SaaS security posture management [citation:10].

## Open-Source GitHub Projects

- **[AEGIS](https://github.com/Eeman1113/aegis)**  
  Self-hosted Streamlit dashboard with live AWS integration for real-time security posture visibility, automated quarterly regression testing, and compliance monitoring. Connects to AWS Security Hub, GuardDuty, IAM, EC2, S3, CloudTrail, and Config; maps findings to SOC2, CIS AWS Benchmark, HIPAA, PCI-DSS, and NIST 800-53. Read-only architecture with no write/delete/mutate calls; multi-account visibility via AWS Organizations [citation:21].

- **[AWS IAM Dashboard](https://github.com/AWS-IAM-Dashboard/IAM-Dashboard)**  
  Cloud-security dashboard automating IAM misconfiguration detection and visualization. Built with OPA, Checkov, and Gitleaks; deployed via S3, Lambda, DynamoDB, API Gateway, Docker, and Vite. Features JWT-based authentication, role-based access control, API rate limiting, and Grafana/Prometheus integration for security metrics. Terraform deployment modules included [citation:17].

- **[Paladin Cloud (Community Edition)](https://github.com/d-demirci/PaladinCloudCE)**  
  Extensible, Security-as-Code cloud security platform for multi-cloud and hybrid environments. Performs continuous asset discovery, policy evaluation, and auto-fix for violations. Features dynamic asset grouping for scoped compliance views, exception management, role-based access control, OAuth2/Azure AD integration, and support for unlimited AWS, Azure, and GCP accounts [citation:25].

- **[warden](https://github.com/casareanderson/warden)**  
  Lightweight, self-hosted security console for homelab or small estate. Reads reverse-proxy and SSO logs, sweeps LAN, scans containers for vulnerabilities, watches files for drift, tracks AI-agent activity, and offers Cloudflare edge bans. Detect-only by default with explicit approval required for enforcement actions; MCP and REST interfaces are read-only [citation:24].

- **[XCLOAK Security Suite](https://github.com/The-Abishek1/XCLOAK-SECURITY-SUITE)**  
  Open-source enterprise SOC platform combining SIEM, SOAR, EDR, DPI, MDM, and NGFW in one self-hosted stack. Detection engines cover DNS anomalies, TLS anomalies, HTTP inspection, protocol anomalies, port scanning, exfiltration, credential attacks, privilege escalation, ransomware, and LotL techniques. Go agent provides autonomous collectors for processes, connections, users, packages, auth logs, and file integrity monitoring [citation:22].

### Additional Strong Open-Source Options

- **[Wazuh](https://github.com/wazuh/wazuh)** — Open-source XDR and SIEM with security dashboards for threat detection, file integrity monitoring, and compliance reporting.
- **[TheHive](https://github.com/TheHive-Project/TheHive)** — Security incident response platform with case management and MISP integration.
- **[Graylog](https://github.com/Graylog2/graylog2-server)** — Log management and SIEM platform with MITRE ATT&CK-aligned security dashboards and anomaly detection.
- **[PolySIEM](https://github.com/Realynx/PolySIEM)** — Self-hosted homelab SIEM with Proxmox/OPNsense/Elastic sync, Suricata threat intel, and security scoring.
- **Community security-dashboard topic** — 73+ public repositories on GitHub covering Wazuh reporting, WAF interfaces, phishing detection, and UEBA dashboards [citation:16].

**Frameworks for building custom systems**: Combine **AEGIS** for AWS posture visibility, **Paladin Cloud** for multi-cloud policy enforcement, **Wazuh** for SIEM/endpoint telemetry, and **Grafana** for unified dashboards—or deploy **XCLOAK** for an all-in-one self-hosted SOC stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
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
