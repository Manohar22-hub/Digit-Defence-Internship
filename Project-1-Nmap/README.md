# 🔐 Nmap – Network Scanning and Security Auditing

## 📌 Project Overview

This project demonstrates the practical use of **Nmap (Network Mapper)** for network discovery, port scanning, service and version detection, operating system fingerprinting, and vulnerability assessment.

The project was performed in a **controlled virtual laboratory environment** using Kali Linux and Metasploitable 2. The objective was to understand how Nmap can be used for network reconnaissance, security auditing, vulnerability identification, and risk analysis.

---

## 🎯 Objectives

* Understand the architecture, features, and working principles of Nmap.
* Install and configure Nmap in a controlled laboratory environment.
* Perform host discovery and port scanning.
* Identify services and software versions running on open ports.
* Perform operating system detection and fingerprinting.
* Use Nmap Scripting Engine (NSE) for vulnerability assessment.
* Analyze security risks and document mitigation recommendations.

---

## 🛠️ Tools & Technologies

* **Nmap**
* **Kali Linux**
* **Metasploitable 2**
* **Oracle VirtualBox**
* **Linux**
* **Nmap Scripting Engine (NSE)**

---

## 🧪 Test Environment

```text
Kali Linux
    │
    │ Nmap
    ▼
Metasploitable 2
```

The assessment was conducted within an isolated/controlled virtual laboratory environment.

---

## 🔎 Methodology

The project followed the following workflow:

```text
Host Discovery
      ↓
Port Scanning
      ↓
Service & Version Detection
      ↓
OS Detection
      ↓
Aggressive Scanning
      ↓
NSE Vulnerability Assessment
      ↓
Risk Analysis
      ↓
Documentation
```

---

## ⚙️ Scans Performed

### Host Discovery

```bash
nmap -sn <target>
```

Used to identify active/reachable hosts on the target network.

### Port Scanning

```bash
nmap <target>
```

Used to identify open, closed, and filtered ports.

### Service & Version Detection

```bash
nmap -sV <target>
```

Used to identify services and their versions running on open ports.

### OS Detection

```bash
nmap -O <target>
```

Used to attempt operating system identification through fingerprinting.

### Aggressive Scan

```bash
nmap -A <target>
```

Used to gather additional information including OS detection, service information, scripts, and traceroute.

### NSE Vulnerability Assessment

```bash
nmap --script=vuln <target>
```

Used to perform vulnerability-related checks through the Nmap Scripting Engine.

---

## ⚠️ Key Vulnerabilities Identified

The assessment identified vulnerabilities across different severity levels, including:

| Severity    | Vulnerabilities                                                  |
| ----------- | ---------------------------------------------------------------- |
| 🔴 Critical | vsFTPd 2.3.4 Backdoor, UnrealIRCd Backdoor                       |
| 🟠 High     | SSL POODLE, Logjam, SSL CCS Injection, Diffie-Hellman weaknesses |
| 🟡 Medium   | HTTP CSRF, Missing HttpOnly Cookie Flag                          |

---

## 📊 Risk Analysis

The identified vulnerabilities were analyzed according to their potential security impact.

Major risks included:

* Unauthorized access
* Remote command execution
* Man-in-the-Middle attacks
* Weak cryptographic protection
* Session-related security risks
* Web application security weaknesses

Recommended security measures included patching vulnerable software, disabling unnecessary services, strengthening cryptographic configurations, and performing regular security assessments.

---

## 📸 Project Screenshots

Screenshots demonstrating the practical activities are available in:

**`Screenshots/`**

These include host discovery, port scanning, service/version detection, OS detection, aggressive scanning, and NSE vulnerability assessment.

---

## 📄 Project Documentation

**Final Report:**
`Report/Nmap_Project_Final_Report.pdf`

**Presentation:**
`Presentation/Nmap_Project_Presentation.pptx`

---

## 📚 Key Learning Outcomes

Through this project, I gained practical experience in:

* Network reconnaissance
* Port and service enumeration
* OS fingerprinting
* Vulnerability assessment
* NSE scripting
* Security risk analysis
* Network security documentation

---

## ⚠️ Disclaimer

All security testing was performed in a **controlled and authorized laboratory environment for educational purposes**.

The techniques demonstrated in this project should only be used against systems and networks for which proper authorization has been obtained.

---

## 👨‍💻 Author

**Manohar Chowdary**

Cybersecurity | Network Security | SOC Operations

