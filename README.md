# 🔐 Web Application Security Testing Lab

## 📌 Overview

This project demonstrates basic **web application security testing** using a vulnerable login application.

The goal of this project is to understand:

* How vulnerabilities exist in applications
* How attackers exploit them
* How to analyze and fix them

---

## 🏗️ Project Structure

```
product-security-lab/
│
├── vulnerable-app/        # Node.js login application
├── threat-modeling/       # Threat analysis (TARA)
├── pentest-reports/       # Nmap & ZAP reports
├── sbom/                  # Dependency list (SBOM)
├── vulnerability-scanner/ # Vulnerability analysis report
└── README.md
```

---

## 🚀 Features

### 🔹 Vulnerable Login Application

* Built using Node.js and SQLite
* Contains intentional SQL Injection vulnerability
* Used for testing and learning purposes

---

### 🔹 Threat Modeling (TARA)

* Identified:

  * Assets (user credentials)
  * Entry points (login form)
  * Threats (SQL Injection, XSS)
* Performed basic risk assessment

---

### 🔹 Network Scanning (Nmap)

* Scanned localhost to identify open ports
* Discovered running services and potential attack surface

---

### 🔹 Web Vulnerability Scanning (OWASP ZAP)

* Performed basic web application scanning using OWASP ZAP
* Explored automated vulnerability detection
* Identified common issues such as:

  * Input-based vulnerabilities
  * Missing security headers

---

### 🔹 SBOM (Software Bill of Materials)

* Generated using CycloneDX
* Listed all dependencies used in the application
* Helps identify supply chain risks

---

### 🔹 Vulnerability Analysis

| Vulnerability   | Risk Level  | Impact                   |
| --------------- | ----------- | ------------------------ |
| SQL Injection   | 🔴 Critical | Authentication bypass    |
| XSS             | 🟠 High     | Script execution         |
| Missing Headers | 🟡 Medium   | Reduced browser security |

---

## 🛠️ Tools Used

* Node.js
* Express.js
* SQLite
* Nmap
* OWASP ZAP


---

## 🔥 Key Learning

* Understood how SQL Injection works
* Performed port scanning using Nmap
* Explored web vulnerability scanning using OWASP ZAP
* Generated SBOM for dependency tracking
* Analyzed vulnerabilities based on risk level

---

## 📷 Example Attack

```
' OR 1=1 --
```

👉 This payload bypassed login authentication due to SQL Injection vulnerability.

---

## 🎯 Conclusion

This project helped in understanding how vulnerabilities are identified and analyzed in a web application.
It also demonstrates basic security concepts required for roles like SOC Analyst and Security Engineer.

---

## 📢 Author

**Sahil Chougale**
Aspiring Cybersecurity Analyst 🚀
