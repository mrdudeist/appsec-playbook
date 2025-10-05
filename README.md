# AppSec & IAM Playbook

This repository contains **experience-based security guides** focused on  
**Application Security (AppSec)** and **Identity & Access Management (IAM)** practices in enterprise environments.

Each guide reflects **industry-standard processes**, lessons learned from real operational experience,  
and repeatable methods for improving the security posture of complex systems —  
without referencing any specific organization or confidential data.

---

## 📘 Purpose

To build a structured, reusable knowledge base covering:

- Application and infrastructure hardening
- Vulnerability remediation and change control
- Identity and access governance
- Secure operations and compliance alignment

---

## 🧩 Repository Structure

appsec-iam-playbook/

├── README.md

└── guides/

    ├── tls-hardening-guide.md ← Secure TLS configuration and cipher hardening
    ├── iam_rbac-baseline-guide.md ← (planned) RBAC and access control baseline
    └── ... (TBD)

---

## 🧠 Topics Covered

### 🧱 Application Security (AppSec)
- TLS / Cipher Suite hardening  
- Vulnerability remediation workflow  
- Secure change management and rollback  
- Dependency and integration validation  
- Continuous security improvement in enterprise systems  

### 🔐 Identity & Access Management (IAM)
- RBAC design and least privilege principles  
- Privileged Access Management (PAM)  
- Access review and certification processes  

---

## 📂 Example Guide

[🔹 AppSec Guide: TLS Hardening and Cipher Suite Remediation](cases/tls_hardening_guide.md)  
A structured approach for securely disabling legacy TLS versions and weak cipher suites  
while maintaining system stability and audit compliance.

---

## 🧭 Roadmap

- [ ] Add IAM guide: RBAC baseline and SoD enforcement  
- [ ] Add AppSec guide: CVE remediation workflow  
- [ ] Add AppSec guide: SAST/SCA findings triage process  
- [ ] Add IAM guide: JML lifecycle and access recertification  
- [ ] Include simple process diagrams for each guide  

---

## 👤 About

**Dmitrii** — IT professional with 7 years of experience in **Application Management**,  
**IT Service Delivery**, and **Compliance**.  
Focused on bridging **Operations and Security** through practical AppSec and IAM methodologies.

💻 [GitHub](https://github.com/mrdudeist)

---

### ⚠️ Disclaimer

All materials in this repository are **generic**.  
They represent **commonly accepted security practices** derived from professional experience.  
No proprietary data, system details, or company-specific information are included.
