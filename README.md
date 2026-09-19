# ⚡ Kartavya Joshi | Cybersecurity Engineer & Cyber Resilience Specialist

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=26&pause=1000&color=00FF41&center=true&vCenter=true&width=900&lines=DEFENDING+CRITICAL+INFRASTRUCTURE;OT+%2F+ICS+SECURITY+SPECIALIST;FIRMWARE+%26+EMBEDDED+VULN+RESEARCHER;BLUE+TEAM+OPERATIONS+%26+SOC+DEFENSE;BUILDING+SYSTEMIC+CYBER+RESILIENCE" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://in.linkedin.com/in/kartavyajoshi"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/Kartavyajoshi"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://tryhackme.com/p/joshi.kartavyaa"><img src="https://img.shields.io/badge/TryHackMe-C1121F?style=for-the-badge&logo=tryhackme&logoColor=white" alt="TryHackMe" /></a>
  <a href="mailto:joshi.kartavyaa@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://kartavyajoshi.github.io/WINSECURE/"><img src="https://img.shields.io/badge/WinSecure_Platform-00FF41?style=for-the-badge&logo=windows&logoColor=black" alt="WinSecure" /></a>
</p>

---

## 👨‍💻 Executive Summary

I am an **M.Tech Cybersecurity & Cyber Resilience candidate** at the **National Forensic Sciences University (NFSU)** (School of Cyber Security & Digital Forensics) and a **B.Tech Computer Science graduate (CPI: 9.61 / 10)**.

My research and engineering practice focuses on **Operational Technology (OT) / ICS Security**, **Vulnerability Research & Firmware Reverse Engineering**, **Defensive SOC & SIEM Operations**, and **Deterministic Endpoint Posture Auditing**. I specialize in securing air-gapped industrial environments, analyzing proprietary control protocols, uncovering embedded vulnerabilities (responsible disclosure), and building offline-resilient security architectures.

- 🎓 **Education**: M.Tech in Cybersecurity & Cyber Resilience (**NFSU**) | B.Tech in CSE (**9.61 CPI**, **10/10 SPI** in Sem 2 & 7)
- 🎯 **Recognitions**: **GATE Qualified** | 4+ Industry Internships (SOC Operations, Blockchain, AI/ML, IoT)
- 📜 **Certifications**: Certified in Cybersecurity (**ISC² CC**), Google Cybersecurity Professional, EC-Council (EHE)
- 🔬 **Research Focus**: AI-driven deception honeypots, firmware binary dissection (MIPS/ARM), and industrial SCADA resilience
- 📍 **Location**: Ahmedabad / Gandhinagar, India

---

## 🏭 Operational Technology (OT) & ICS Security Focus

Defending industrial environments demands safety-critical, protocol-deterministic engineering that fundamentally differs from enterprise IT. My OT/ICS practice spans architecture mapping, protocol telemetry forensics, and air-gapped cyber-physical system defense:

```
+-----------------------------------------------------------------------------------------+
|                               PURDUE MODEL & DEFENSE LAYERS                             |
+-----------------------------------------------------------------------------------------+
|  Level 4/5 : Enterprise & Cloud   --> IT/OT DMZ (Data Diodes, Strict Jump Hosts, NGFW)  |
|  Level 3   : Site Operations      --> Historians, SCADA Servers, OT SIEM & Zeek Monitor |
|  Level 2   : Supervisory Control  --> HMIs, Engineering Workstations (EWS Hardening)   |
|  Level 1   : Local Automation     --> PLCs (ABB, Siemens), RTUs, IEDs (Logic Integrity) |
|  Level 0   : Physical Process     --> Actuators, Sensors, Drives, Safety Relays         |
+-----------------------------------------------------------------------------------------+
```

### 🔹 Industrial Protocols & Telemetry Forensics
- **Deep Packet Inspection & PCAP Analysis**: Function-code auditing, unauthorized write prevention, and anomaly triage for **Modbus (TCP/RTU)**, **DNP3**, **IEC 60870-5-104**, **IEC 61850**, **Ethernet/IP**, **Profinet**, and **OPC UA**.
- **Hardware & PLC Assessment**: Hands-on evaluation of industrial controllers (e.g., ABB AC500 / PM564-ETH series), ladder logic validation, and firmware integrity inspection.

### 🔹 Standards, Governance & Frameworks
- **ISA/IEC 62443**: Translating Security Levels (SL 1–4) into practical conduit & zone microsegmentation policies for IACS.
- **NIST SP 800-82 (Rev 3)**: Implementing cyber-physical safeguards prioritizing availability, safety-instrumented systems (SIS), and non-disruptive monitoring.
- **MITRE ATT&CK® for ICS**: TTP mapping covering initial access, execution, inhibition of response functions, and manipulation of control telemetry.

### 🔹 OT Cyber Resilience & Air-Gapped Architecture
- **Zero-Cloud Air-Gapped Operation**: Building inspection tools and forensic workflows that run 100% offline with zero external network dependencies.
- **Industrial Deception & Threat Modeling**: Utilizing ICS honeypots (e.g., Conpot integration) to model adversary reconnaissance against SCADA assets.

## 🚀 Featured Engineering Projects

### 🛡️ [WinSecure — Automated Cybersecurity Assessment & Posture Platform](https://github.com/Kartavyajoshi/WINSECURE)
> **Platform**: Python 3.9+ | Windows 10/11/Server | **108 Tests Passing** | [Live Website & Threat Matrix](https://kartavyajoshi.github.io/WINSECURE/)

An enterprise-grade, deterministic, non-destructive Windows configuration auditing engine engineered for high-security and air-gapped environments:
- **36 Security Domains & 62+ Defensive Assertions**: Evaluates LSA RunAsPPL, Credential Guard, VBS/HVCI, CET shadow stacks, Controlled Folder Access, WDAC, and SMB/RDP hardening.
- **Academic Rigor**: Formulates Bayesian Attack Graphs (*IEEE TDSC*), Kill-Chain blast radius correlation, and computes a **Ransomware Defense Index (RDI)**.
- **Zero Trust & Compliance Mapping**: Assesses posture against CISA Zero Trust Maturity Model (ZTMM v2.0), CIS Controls v8, NIST SP 800-53 Rev 5, DISA STIG, and Microsoft Baselines.
- **Air-Gapped & SIEM Ready**: 100% offline execution with zero cloud telemetry; exports interactive HTML, SARIF, JSON, and NDJSON for Splunk, Elastic, and Microsoft Sentinel.

---

### 🔍 [IntelCore-OSINT — Threat Intelligence & Passive Reconnaissance Platform](https://github.com/Kartavyajoshi/IntelCore-OSINT)
> **Stack**: Python | OSINT APIs | Attack Surface Intelligence

A professional-grade intelligence gathering framework that automates external attack surface discovery:
- **Multi-Vector Intelligence**: Aggregates and correlates telemetry across 11 modules including Shodan, VirusTotal, and DNS forensics.
- **Zero Touch Target Architecture**: Gathers comprehensive reconnaissance metrics without touching or alerting target infrastructure.
- **Actionable Reporting**: Synthesizes threat feeds into structured risk intelligence reports for red/blue team assessments.

---

### 🔬 [Malware Analyzer — Static Binary Dissection & Triage Framework](https://github.com/Kartavyajoshi/MALWARE-ANALYZER)
> **Stack**: Python | PE/ELF Forensics | Reverse Engineering

A multi-format static analysis framework built for incident responders and reverse engineers:
- **Safe Static Inspection**: Dissects suspicious binaries, extracts actionable indicators of compromise (IOCs), and flags anomalous structures without detonation.
- **Deep Triage**: Analyzes PE/ELF headers, section entropy, import/export tables, suspicious API calls, and embedded strings.
- **Forensic Pipeline**: Streamlines command-line triage for fast incident escalation and malware classification.

---

### 🔐 [Secura-Vault — Hardware-Bound Anti-Forensic Cryptographic Vault](https://github.com/Kartavyajoshi/Secura-Vault)
> **Stack**: Python | Cryptography | Zero-Knowledge Architecture

An industrial-grade password management architecture engineered for high-security workstation environments:
- **Zero-Knowledge Storage**: Implements hardware-bound key derivation and cryptographic authentication.
- **Anti-Forensic Controls**: Prevents memory dumping and forensic artifact extraction on local endpoints.

## 🛡️ Core Technical Competencies

| Domain | Key Capabilities & Methodologies |
| :--- | :--- |
| **OT / ICS Security** | ISA/IEC 62443, NIST SP 800-82, Purdue Model, Modbus, DNP3, IEC 60870-5-104, SCADA/PLC Triage |
| **Firmware & Embedded Sec** | MIPS/ARM Disassembly, Ghidra, Binwalk, Firmware Unpacking, CVE Research, PoC Development |
| **Defensive SOC & SIEM** | Log Analysis, Threat Hunting, Splunk, Elastic/ELK, Microsoft Sentinel, Incident Response |
| **System Hardening & Audit** | Windows Internals, CIS Benchmarks, NIST SP 800-53, DISA STIG, Zero Trust (CISA ZTMM) |
| **VAPT & AppSec** | OWASP Top 10, Network Vulnerability Assessment, Authentication/Authorization Flaws |
| **Malware & Reverse Eng** | Static Analysis, PE/ELF Structure Inspection, Header/Entropy Forensics, YARA rules |

---

## 💻 Tech Stack & Tooling

```
Programming & Scripting : Python | C / C++ | Bash | PowerShell | Solidity | Java | SQL
OT / ICS & Network     : Wireshark | Zeek / Suricata | Modbus Tools | Scapy | NetworkMiner | Conpot
Reverse Eng & Analysis : Ghidra | x64dbg | Binwalk | YARA | PEfile | Strings | GDB
Threat Defense & SIEM  : WinSecure | Splunk | Sysmon | Wazuh | OpenVAS
Security Testing       : Nmap | Burp Suite | Metasploit | Shodan | OWASP ZAP | Impacket
Platforms & Systems    : Linux (Kali, Ubuntu) | Windows Server / 11 | Docker | Git
```

---

## 🏆 Highlights & Academic Milestones

| Milestone | Recognition & Details |
| :--- | :--- |
| **M.Tech NFSU** | Cybersecurity & Cyber Resilience at National Forensic Sciences University |
| **B.Tech CSE** | **9.61 CPI** (Graduated with top academic standing) |
| **GATE Exam** | Qualified Computer Science & Information Technology |
| **Industry Internships** | 4+ completed internships across SOC Operations, Blockchain, AI/ML, and IoT domains |
| **Global Certifications** | Certified in Cybersecurity (**ISC² CC**), Google Cybersecurity, EC-Council (EHE) |

---

## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Kartavyajoshi&show_icons=true&theme=tokyonight&hide_border=true&title_color=00FF41&icon_color=00FF41&text_color=c0caf5&bg_color=0d1117" alt="Kartavya's GitHub stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kartavyajoshi&layout=compact&theme=tokyonight&hide_border=true&title_color=00FF41&text_color=c0caf5&bg_color=0d1117" alt="Top Languages" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Kartavyajoshi&theme=tokyonight&hide_border=true&stroke=00FF41&ring=00FF41&fire=00FF41&currStreakNum=00FF41&sideNums=c0caf5&sideLabels=c0caf5&dates=7982a9&background=0d1117" alt="GitHub Streak" />
</p>

---

<p align="center">
  <i>"Resilience is not just defending against attacks—it is ensuring critical processes endure and recover seamlessly."</i>
</p>
