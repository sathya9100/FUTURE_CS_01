# FUTURE_CS_01 – Vulnerability Assessment Report for a Live Website

## Overview

This repository contains the submission for **Task 1** of the **Future Interns Cyber Security Internship**.

The objective of this task was to perform a passive vulnerability assessment on a publicly accessible demonstration web application using industry-standard security tools. The assessment focused on identifying security weaknesses without exploiting the target application or affecting its availability.

---

## Assessment Details

| Item | Description |
|------|-------------|
| Internship | Future Interns – Cyber Security Internship |
| Task | Task 1 – Vulnerability Assessment Report |
| Assessment Type | Passive Web Application Security Assessment |
| Target | TestFire Demo Application (Altoro Mutual) |
| URL | http://demo.testfire.net |
| Assessment Approach | Non-destructive / Passive Testing |

---

## Objectives

The assessment was performed to:

- Identify common web application vulnerabilities
- Perform passive reconnaissance using Nmap
- Analyze HTTP requests and responses using OWASP ZAP
- Classify vulnerabilities according to their severity
- Recommend appropriate remediation measures
- Document the assessment following professional reporting standards

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Nmap | Network reconnaissance and service discovery |
| OWASP ZAP | Passive web application security assessment |
| Browser Developer Tools | Verification of requests, responses, and headers |
| Google Chrome | Accessing the target application |
| Microsoft Word | Documentation and report preparation |

---

## Assessment Methodology

The assessment followed a structured methodology consisting of five stages:

### 1. Target Selection

The TestFire demonstration application was selected because it is intentionally designed for cybersecurity training and vulnerability assessment.

### 2. Network Reconnaissance

Nmap was used to identify accessible services and collect basic information about the target host.

### 3. Passive Web Application Assessment

OWASP ZAP was configured in Passive Scan mode to inspect HTTP traffic and identify security issues without sending malicious payloads.

### 4. Manual Verification

The reported findings were reviewed using Browser Developer Tools and the generated OWASP ZAP report.

### 5. Documentation

All findings, screenshots, observations, risk classifications, and recommendations were documented in a structured vulnerability assessment report.

---

## Summary of Findings

| Severity | Findings |
|----------|---------:|
| High | 2 |
| Medium | 4 |
| Low | 4 |
| Informational | 3 |

### High Risk

- Reflected Cross-Site Scripting (XSS)
- SQL Injection

### Medium Risk

- Absence of Anti-CSRF Tokens
- Content Security Policy Header Not Set
- Missing Anti-Clickjacking Header
- Missing Subresource Integrity (SRI)

### Low Risk

- Cookie Without SameSite Attribute
- Cross-Domain JavaScript Source File Inclusion
- Server Version Information Disclosure
- Missing X-Content-Type-Options Header

### Informational

- Information Disclosure – Suspicious Comments
- Modern Web Application Detection
- Session Management Response Identified

---

## Repository Structure

```text
FUTURE_CS_01
│
├── README.md
│
├── Report
│   ├── Vulnerability_Assessment_Report.pdf
│   ├── zap_report.html
│   └── zap_report/
│
└── Screenshots
    ├── alerts.png
    ├── nmap_scan.png
    ├── zap_scan.png
    └── zap_report.png
```

---

## Supporting Evidence

### Nmap Scan

<img src="Screenshots/nmap_scan.png" width="900">

### OWASP ZAP Scan Completion

<img src="Screenshots/zap_scan.png" width="900">

### Security Alerts

<img src="Screenshots/alerts.png" width="900">

### Generated HTML Report

<img src="Screenshots/zap_report.png" width="900">

---

## Key Learning Outcomes

This task provided practical experience in:

- Passive vulnerability assessment
- Web application security testing
- Reconnaissance using Nmap
- Security analysis using OWASP ZAP
- Risk classification
- Professional cybersecurity documentation
- Ethical vulnerability assessment practices

---

## Disclaimer

This assessment was conducted exclusively on an authorized demonstration website intended for cybersecurity education and training.

No exploitation, denial-of-service testing, authentication bypass, or unauthorized activities were performed during this assessment.

---

## Author

**Sathya Ankitha Ravirala**

Cyber Security Intern  
Future Interns

GitHub: https://github.com/sathya9100

LinkedIn: https://www.linkedin.com/in/sathya-ankitha-ravirala