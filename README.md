# Botium Toys: Comprehensive Internal Security Audit & Compliance Assessment

Welcome to the **Botium Toys Internal Security Audit** repository. This project contains a rigorous, comprehensive security program assessment, risk evaluation, controls checklist, and regulatory compliance analysis conducted for Botium Toys.

---

## 📁 Repository Structure

```text
📁 botium-toys-security-audit/
├── 📄 README.md                             # Project overview and documentation
├── 📁 reports/
│   └── 📄 Botium_Toys_Internal_Security_Audit_Report.pdf  # Full formal security audit report
└── 📁 source-docs/
    ├── 📄 Botium Toys Scope, goals, and risk assessment report.docx
    └── 📄 Controls and compliance checklist.pdf
```

---

## 📋 Executive Summary & Key Findings

- **Overall Risk Score:** **8 / 10 (High Risk)**
- **Primary Risk Drivers:** Inadequate asset management, unencrypted local cardholder data, lack of role-based access control (Least Privilege & Separation of Duties), absence of an Intrusion Detection System (IDS), and no disaster recovery or backup plans.
- **Physical Security Strengths:** Excellent physical access controls (robust locks, CCTV surveillance) and functioning fire detection/suppression systems.

---

## 🛡️ Controls Assessment Summary

| Security Control | Status | Assessment Notes |
| :--- | :---: | :--- |
| **Least Privilege** | ❌ No | All employees currently have broad access to internal data, PII, and cardholder data. |
| **Separation of Duties** | ❌ No | Not currently implemented across operational roles. |
| **Disaster Recovery Plans** | ❌ No | No disaster recovery plans currently in place. |
| **Password Policies** | ✅ Yes | Nominal policy exists, but requires hardening (special characters, complexity). |
| **Firewall** | ✅ Yes | Configured with appropriately defined security rules blocking unauthorized traffic. |
| **Intrusion Detection System (IDS)** | ❌ No | Not installed; network traffic lacks automated anomaly detection. |
| **Backups** | ❌ No | No backups of critical data currently maintained. |
| **Antivirus Software** | ✅ Yes | Installed and monitored regularly by the IT department. |
| **Legacy System Maintenance** | ✅ Yes | Manually monitored and maintained, though lacking a regular schedule. |
| **Encryption** | ❌ No | Credit card information and local database records are unencrypted. |
| **Password Management System** | ❌ No | No centralized password manager; heavy reliance on IT support tickets. |
| **Physical Locks & CCTV** | ✅ Yes | Sufficient physical security and up-to-date CCTV monitoring active. |
| **Fire Detection & Prevention** | ✅ Yes | Functioning fire alarms and sprinkler systems installed. |

---

## ⚖️ Regulatory Compliance Evaluation

- **PCI DSS:** Currently **non-compliant** due to unencrypted card data storage/processing and unrestricted employee access.
- **GDPR:** Partial compliance (established 72-hour breach notification plan and privacy enforcement, but lacking proper data inventory, classification, and strict access controls).
- **SOC 1 & SOC 2:** Requires remediation in user access policies, PII confidentiality controls, and data protection safeguards.

---

## 🚀 Strategic Recommendations & Roadmap

1. **Asset Classification & Inventory:** Dedicate resources under NIST CSF *Identify* to inventory hardware, software, and data repositories.
2. **Access Control Hardening:** Enforce the Principle of Least Privilege and Role-Based Access Control (RBAC).
3. **Data Encryption:** Implement robust encryption for all credit card transactions and local storage.
4. **Network Defense Enhancement:** Deploy an automated Intrusion Detection System (IDS).
5. **Disaster Recovery & Backups:** Establish comprehensive disaster recovery plans and automated backups.
6. **Credential Management:** Modernize password complexity rules and deploy an enterprise password manager.

---
*Generated as part of cybersecurity studies and practical risk assessment projects.*
