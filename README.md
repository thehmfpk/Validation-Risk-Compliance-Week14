# Validation Risk Compliance Week14

## Software Verification & Validation Lab Project

This repository contains the complete implementation of the Week 14 Software Verification & Validation lab assignment titled:

> **Validation Risk Structuring and Compliance Evidence Compilation**

The project demonstrates the process of software security validation, vulnerability assessment, risk structuring, compliance evidence compilation, and audit documentation using OWASP ZAP by Checkmarx.

---

# Project Objective

The objective of this project was to perform security validation on a demo web application and organize all findings into a structured compliance dossier suitable for audit review.

The project focuses on:

- Security validation
- Vulnerability detection
- Validation risk structuring
- Compliance evidence collection
- Risk mitigation planning
- Audit documentation
- Security reporting

---

# Target Application

Target Website Scanned:

https://www.hafizmfaizan.site

---

# Tool Used

## OWASP ZAP by Checkmarx

OWASP ZAP (Zed Attack Proxy) was used to perform passive security scanning and vulnerability analysis on the target web application.

### Purpose of OWASP ZAP

- Detect security vulnerabilities
- Analyze HTTP security headers
- Identify insecure configurations
- Detect information disclosure issues
- Generate security validation reports

Official Website:

https://www.zaproxy.org/

---

# Validation Activities Performed

## 1. Security Scanning

Security validation scanning was performed using OWASP ZAP against the target application.

The scan included:

- Passive vulnerability scanning
- Header security analysis
- Cross-domain configuration analysis
- Information disclosure detection
- Cache-control validation

---

## 2. Vulnerability Detection

The following vulnerabilities were identified during scanning:

| Vulnerability | Severity |
|---|---|
| Content Security Policy (CSP) Header Not Set | Medium |
| Cross-Domain Misconfiguration | Medium |
| Missing Anti-clickjacking Header | Medium |
| Sub Resource Integrity Missing | Medium |
| Cross-Domain JavaScript Inclusion | Low |
| X-Content-Type-Options Header Missing | Low |
| Sensitive Information in URL | Informational |
| Suspicious Comments | Informational |
| Cache-Control Weakness | Informational |

---

## 3. Risk Structuring

All detected vulnerabilities were converted into structured validation risks.

Each risk contains:

- Risk ID
- Risk Description
- Source Evidence
- Probability
- Impact
- Risk Level
- Mitigation Actions

---

## 4. Compliance Evidence Compilation

All validation evidence was organized into a professional compliance dossier including:

- Security reports
- Risk registers
- Validation logs
- Vulnerability summaries
- Security screenshots
- Final audit documentation

---

# Repository Structure

```text
Validation-Risk-Compliance-Week14/
│
├── SecurityReports/
│   ├── README.md
│   └── ZAP by Checkmarx Scanning Report.pdf
│
├── RiskRegisters/
│   ├── README.md
│   └── Risk_Register.xlsx
│
├── ComplianceDossier/
│   ├── README.md
│   ├── Vulnerability_Summary.docx
│   └── Final_Compliance_Dossier.docx
│
├── EvidenceScreenshots/
│   ├── README.md
│   ├── zap_dashboard.png
│   ├── alerts.png
│   └── github_repo.png
│
└── README.md

