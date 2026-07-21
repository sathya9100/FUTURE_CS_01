# 🛡️ Future Interns – Cyber Security Internship

![Internship](https://img.shields.io/badge/Internship-Future%20Interns-blue)
![Task](https://img.shields.io/badge/Task-1-green)
![Tool](https://img.shields.io/badge/Tool-OWASP%20ZAP-orange)
![Tool](https://img.shields.io/badge/Tool-Nmap-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

# 🔍 Task 1 – Vulnerability Assessment Report for a Live Website

## 📌 Objective

The objective of this task was to perform a passive vulnerability assessment on a live demonstration web application using industry-standard cybersecurity tools. The assessment focused on identifying security weaknesses without exploiting or modifying the target application.

---

# 🎯 Target Website

**Website:** TestFire Demo Application (Altoro Mutual)

**URL:** http://demo.testfire.net

> **Note:** This is an intentionally vulnerable web application designed for cybersecurity learning and testing purposes.

---

# 🛠️ Tools Used

- Nmap
- OWASP ZAP (Zed Attack Proxy)
- Browser Developer Tools
- Google Chrome
- Microsoft Word

---

# 📋 Assessment Methodology

The vulnerability assessment was conducted using the following steps:

1. Target Selection
2. Network Reconnaissance using Nmap
3. Passive Web Application Assessment using OWASP ZAP
4. Manual Verification of Findings
5. Documentation and Report Preparation

---

# 🚨 Vulnerabilities Identified

### High Risk

- Reflected Cross-Site Scripting (XSS)
- SQL Injection

### Medium Risk

- Absence of Anti-CSRF Tokens
- Content Security Policy (CSP) Header Not Set
- Missing Anti-Clickjacking Header
- Subresource Integrity (SRI) Attribute Missing

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

# 📊 Risk Summary

| Risk Level | Count |
|------------|------:|
| 🔴 High | 2 |
| 🟠 Medium | 4 |
| 🟡 Low | 4 |
| 🔵 Informational | 3 |

---

# 📂 Repository Structure

```text
FUTURE_CS_01/
│
├── README.md
│
├── Report/
│   ├── Vulnerability_Assessment_Report.pdf
│   ├── zap_report.html
│   └── zap_report/
│
└── Screenshots/
    ├── alerts.png
    ├── nmap_scan.png
    ├── zap_scan.png
    └── zap_report.png
```

---

# 📸 Project Screenshots

## Nmap Scan

![Nmap Scan](Screenshots/nmap_scan.png)

---

## OWASP ZAP Scan Completion

![OWASP ZAP Scan](Screenshots/zap_scan.png)

---

## Security Alerts

![Alerts](Screenshots/alerts.png)

---

## Generated HTML Report

![HTML Report](Screenshots/zap_report.png)

---

# 📄 Report

The complete vulnerability assessment report is available in the **Report** folder.

**Report Includes:**

- Executive Summary
- Objective
- Scope
- Target Website
- Tools Used
- Methodology
- Findings
- Risk Classification
- Screenshots
- Recommendations
- Conclusion
- References

---

# 🎯 Learning Outcomes

Through this task, I learned how to:

- Perform passive vulnerability assessments
- Conduct network reconnaissance using Nmap
- Use OWASP ZAP for web application security testing
- Identify common web application vulnerabilities
- Classify vulnerabilities based on severity
- Document findings in a professional security assessment report
- Apply ethical cybersecurity assessment practices

---

# ⚠️ Disclaimer

This vulnerability assessment was conducted **only on an authorized demonstration website** for educational purposes as part of the **Future Interns Cyber Security Internship**.

No exploitation, unauthorized access, or malicious activity was performed during this assessment.

---

# 👩‍💻 Author

**Sathya Ankitha Ravirala**

**Future Interns – Cyber Security Intern**

GitHub: https://github.com/sathya9100

LinkedIn: https://www.linkedin.com/in/sathya-ankitha-ravirala-731b27360

---

## ⭐ If you found this project helpful, feel free to star the repository!