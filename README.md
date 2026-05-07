# 🔐 Vulnerability Assessment and Penetration Testing of Web Application

![Cybersecurity](https://img.shields.io/badge/Domain-Cybersecurity-red?style=flat&logo=shield&logoColor=white)
![VAPT](https://img.shields.io/badge/Type-VAPT-darkred?style=flat)
![SQL Injection](https://img.shields.io/badge/Vulnerability-SQL%20Injection-orange?style=flat)
![Status](https://img.shields.io/badge/Status-Completed-green?style=flat)
![Report](https://img.shields.io/badge/Report-PDF%20Available-blue?style=flat)

---

## 📌 Project Overview

This project is an academic study on **Vulnerability Assessment and Penetration Testing (VAPT)** of a web application. The goal is to understand how real-world web vulnerabilities work, how attackers exploit them, and how developers can defend against them.

The project involved researching common web vulnerabilities — with a focus on **SQL Injection** — and documenting the entire assessment process in a detailed report.

---

## 🎯 Objectives

- Understand the VAPT process and methodology
- Study how SQL Injection and other web vulnerabilities work
- Learn how to assess a web application for security weaknesses
- Document findings and suggest remediation strategies
- Develop awareness of ethical hacking practices

---

## 🛠️ Methodology

This project follows the standard VAPT methodology:

1. **Reconnaissance** — Gathering information about the target application
2. **Scanning & Enumeration** — Identifying open ports, services, and entry points
3. **Vulnerability Assessment** — Identifying known vulnerability types
4. **Analysis** — Understanding how SQL Injection attacks work in practice
5. **Reporting** — Documenting the full process with findings and fixes

---

## 🚨 Vulnerabilities Studied

### SQL Injection
- Studied how attackers inject malicious SQL queries through input fields
- Understood authentication bypass techniques using SQL payloads
- Researched error-based, blind, and time-based SQL Injection types
- **Impact**: Unauthorized database access, data leakage, authentication bypass
- **Prevention**: Use parameterized queries, prepared statements, input validation

---

## 📋 Common Vulnerabilities Covered in Report

| Vulnerability | Severity | Description | Recommendation |
|---|---|---|---|
| SQL Injection | 🔴 Critical | Unsanitized input allows raw SQL execution | Use parameterized queries |
| XSS | 🔴 Critical | Scripts injected into web pages | Encode output, use CSP headers |
| Broken Authentication | 🟠 High | Weak session management | Enforce strong auth & session policies |
| Security Misconfiguration | 🟠 Medium | Default/insecure server settings | Harden server configuration |
| Sensitive Data Exposure | 🟡 Medium | Unencrypted sensitive data | Use HTTPS, encrypt stored data |

---

## 🔧 Tools Studied

- **OWASP ZAP** — Automated web vulnerability scanner
- **Burp Suite** — HTTP interception and manipulation
- **Nmap** — Network scanning and enumeration
- **SQLMap** — Automated SQL Injection detection tool
- **OWASP Top 10** — Industry standard vulnerability reference

---

## 📄 Project Report

A detailed PDF report is included in this repository covering:
- Introduction to VAPT
- Web application security concepts
- SQL Injection — types, examples, and prevention
- Full methodology and findings documentation
- Recommendations and remediation strategies

📥 **[View Report](./report/VAPT_Report.pdf)**

---

## 📁 Project Structure

```
├── report/
│   └── VAPT_Report.pdf         # Full vulnerability assessment report
├── methodology/
│   └── testing_steps.md        # Step-by-step methodology documentation
└── README.md
```

---

## 💡 Key Learnings

- Understood how SQL Injection works at a deep technical level
- Learned the importance of input validation and sanitization
- Gained knowledge of industry-standard security testing tools
- Understood the OWASP Top 10 and why it matters for developers
- Developed awareness of ethical and legal boundaries in security testing

---

## ⚠️ Disclaimer

> This project is for **educational purposes only**. All research and testing concepts covered here are intended to promote awareness of web security. **Never perform penetration testing on systems without explicit written permission.**

---

## 📚 References

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [OWASP Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)
- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)

---

## 👨‍💻 Author

**Vaidya Sriman Narayana**
B.Tech — Computer Science & IT
📍 Hyderabad, India
🔗 [GitHub](https://github.com/vaidyasrimannarayana)
