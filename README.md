# Hands-on-SOAR-Threat-Intel-Zero-Trust-Kubernetes-Container-Security-CTF-Labs-SecByte-Index
A practical collection of cybersecurity CTF labs covering Security Orchestration, Automation and Response (SOAR), Threat Intelligence &amp; OSINT, Zero Trust Architecture, IAM Core, Docker &amp; Kubernetes Security, GCP IAM, and AWS Security Monitoring.
# SOAR, Threat Intelligence, Zero Trust & Container Security CTF Labs

Welcome to the **SOAR, Threat Intelligence, Zero Trust & Container Security CTF Lab Collection**. This repository serves as a structured, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection bridges modern security operations and cloud-native engineering, focusing on **SOAR Automation**, **Threat Intelligence & OSINT**, **Zero Trust Architecture**, **Identity & Access Management (IAM)**, **Container & Kubernetes Hardening**, and multi-cloud security monitoring (**AWS & GCP**).

---

## Lab Collection Index

### 1. Security Automation (SOAR) & Threat Intelligence
* **SOAR Fundamentals: Automation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/soar-fundamentals-automation](https://learn.secbyte.org/ctf/soar-fundamentals-automation)  
  *Focus:* Building basic automation playbooks, integrating API endpoints, and executing automated containment actions for routine SOC alerts.

* **Security Orchestration Automation Foundations**  
  *Lab Link:* [https://learn.secbyte.org/ctf/security-orchestration-automation-foundations](https://learn.secbyte.org/ctf/security-orchestration-automation-foundations)  
  *Focus:* Designing end-to-end security orchestration workflows, interconnecting SIEM, EDR, and firewall management layers to reduce MTTR.

* **Threat Intelligence Essentials**  
  *Lab Link:* [https://learn.secbyte.org/ctf/threat-intelligence-essentials](https://learn.secbyte.org/ctf/threat-intelligence-essentials)  
  *Focus:* Understanding threat intelligence lifecycles, indicator types (IOCs/IOAs), feed curation, and strategic threat modeling.

* **Threat Intelligence Enrichment Fundamentals**  
  *Lab Link:* [https://learn.secbyte.org/ctf/threat-intelligence-enrichment-fundamentals](https://learn.secbyte.org/ctf/threat-intelligence-enrichment-fundamentals)  
  *Focus:* Enriching security logs with context from OSINT feeds, WHOIS databases, reputation scoring APIs, and malware sandbox results.

* **OSINT Tactical Frameworks**  
  *Lab Link:* [https://learn.secbyte.org/ctf/osint-tactical-frameworks](https://learn.secbyte.org/ctf/osint-tactical-frameworks)  
  *Focus:* Leveraging open-source intelligence frameworks for threat actor tracking, infrastructure mapping, domain reconnaissance, and asset discovery.

### 2. Zero Trust & Identity Access Management (IAM)
* **Zero Trust Fundamentals**  
  *Lab Link:* [https://learn.secbyte.org/ctf/zero-trust-fundamentals](https://learn.secbyte.org/ctf/zero-trust-fundamentals)  
  *Focus:* Core principles of Zero Trust Architecture (ZTA)—never trust, always verify, least privilege access, microsegmentation, and continuous verification.

* **Identity Foundations: IAM Core**  
  *Lab Link:* [https://learn.secbyte.org/ctf/identity-foundations-iam-core](https://learn.secbyte.org/ctf/identity-foundations-iam-core)  
  *Focus:* Identity providers (IdPs), authentication protocols (SAML, OAuth2, OIDC), privilege management, and directory service security basics.

### 3. Container & Kubernetes Cloud Security
* **Container Security Basics**  
  *Lab Link:* [https://learn.secbyte.org/ctf/container-security-basics](https://learn.secbyte.org/ctf/container-security-basics)  
  *Focus:* Understanding container architecture security, image layering vulnerabilities, runtime isolation, and registry access control.

* **Docker Security Hardening**  
  *Lab Link:* [https://learn.secbyte.org/ctf/docker-security-hardening](https://learn.secbyte.org/ctf/docker-security-hardening)  
  *Focus:* Hardening Docker daemon configurations, writing secure Dockerfiles, dropping unnecessary capabilities, non-root execution, and CIS benchmark audits.

* **Kubernetes Security Architecture Essentials**  
  *Lab Link:* [https://learn.secbyte.org/ctf/kubernetes-security-architecture-essentials](https://learn.secbyte.org/ctf/kubernetes-security-architecture-essentials)  
  *Focus:* Securing K8s control plane components, configuring Role-Based Access Control (RBAC), applying NetworkPolicies, and pod security standards (PSS).

### 4. Multi-Cloud Security (GCP & AWS)
* **GCP IAM Security Essentials**  
  *Lab Link:* [https://learn.secbyte.org/ctf/gcp-iam-security-essentials](https://learn.secbyte.org/ctf/gcp-iam-security-essentials)  
  *Focus:* Auditing Google Cloud Platform IAM roles, service accounts, resource hierarchy permissions, and policy binding security.

* **AWS Security Monitoring Essentials**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-security-monitoring-essentials](https://learn.secbyte.org/ctf/aws-security-monitoring-essentials)  
  *Focus:* Establishing cloud security telemetry via AWS CloudTrail, VPC Flow Logs, GuardDuty, and Amazon CloudWatch alarms.

---

## Learning Path

### Path A: Security Automation & Threat Intelligence Engineer
1. **Intelligence & OSINT:** Start with [Threat Intelligence Essentials](https://learn.secbyte.org/ctf/threat-intelligence-essentials), [Threat Intelligence Enrichment Fundamentals](https://learn.secbyte.org/ctf/threat-intelligence-enrichment-fundamentals), and [OSINT Tactical Frameworks](https://learn.secbyte.org/ctf/osint-tactical-frameworks).
2. **SOAR Integration:** Build automated workflows in [SOAR Fundamentals: Automation](https://learn.secbyte.org/ctf/soar-fundamentals-automation) and [Security Orchestration Automation Foundations](https://learn.secbyte.org/ctf/security-orchestration-automation-foundations).

### Path B: Zero Trust & Container Security Architect
1. **Identity & Architecture:** Begin with [Zero Trust Fundamentals](https://learn.secbyte.org/ctf/zero-trust-fundamentals) and [Identity Foundations: IAM Core](https://learn.secbyte.org/ctf/identity-foundations-iam-core).
2. **Container & Kubernetes Hardening:** Secure workloads using [Container Security Basics](https://learn.secbyte.org/ctf/container-security-basics), [Docker Security Hardening](https://learn.secbyte.org/ctf/docker-security-hardening), and [Kubernetes Security Architecture Essentials](https://learn.secbyte.org/ctf/kubernetes-security-architecture-essentials).

### Path C: Multi-Cloud Security Specialist
1. **GCP Security:** Audit permissions in [GCP IAM Security Essentials](https://learn.secbyte.org/ctf/gcp-iam-security-essentials).
2. **AWS Operations:** Monitor cloud workloads via [AWS Security Monitoring Essentials](https://learn.secbyte.org/ctf/aws-security-monitoring-essentials).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the corresponding link to open the exercise directly on Learn SecByte.
3. Review scenario directives, architecture topology, and task requirements.
4. Build SOAR playbooks, audit container configurations, analyze OSINT feeds, or harden cloud IAM roles to capture flags.

---

## Target Audience

* **SOAR Engineers & SOC Analysts:** Automate security workflows, enrich incoming alerts, and leverage OSINT tactical frameworks.
* **DevSecOps & Container Security Engineers:** Hardened Docker containers, secure Kubernetes clusters, and enforce image security.
* **Cloud Security Architects:** Implement Zero Trust principles, manage IAM identities, and monitor AWS/GCP cloud environments.
* **Cybersecurity Students:** Acquire hands-on experience across modern cloud-native security disciplines.

---

## Disclaimer

All lab links in this repository direct to official training environments hosted on Learn SecByte. All materials are provided exclusively for authorized security training, defensive engineering, and educational research purposes. Unauthorized testing against external infrastructure is strictly prohibited.
