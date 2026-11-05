# Reinaldy Thendean
**Junior Penetration Tester | Web Application Security | Active Directory Security**

Information Technology graduate (GPA: **3.82/4.00**) with hands-on experience in web application penetration testing and SOC Level 1 operations. Skilled at identifying and validating security vulnerabilities, assessing business impact, and communicating practical remediation recommendations.

📧 reinaldy.thendean3@gmail.com · [LinkedIn](https://www.linkedin.com/in/reinaldy-thendean-5b9aaa335) · [GitHub](https://github.com/dewafanii)

---

## At a Glance

| | |
|---|---|
| **Education** | Bachelor of Information Technology, Universitas Multimedia Nusantara |
| **GPA** | 3.82/4.00 |
| **Experience** | SOC Level 1 Analyst Intern, PT. Sembilan Pilar Semesta |
| **Focus** | Web Application Pentesting · Active Directory Security |
| **Certifications** | CEH, Web Pentest L1 |
| **Currently Learning** | Hack The Box CPTS Path |

---

## Core Skills

| Area | Skills |
|---|---|
| **Web Application Pentesting** | OWASP Top 10, SQL Injection, XSS, IDOR, SSRF, Command Injection, File Upload Bypass, WAF/Filter Evasion |
| **Active Directory Security** | Enumeration, Kerberoasting, AS-REP Roasting, GPO/ACL Abuse, Password Spraying, Pass-the-Hash, Pass-the-Ticket |
| **Post-Exploitation** | Credential Dumping, Linux/Windows Privilege Escalation, LSASS Dumping |
| **Network & Pivoting** | Nmap, SSH Tunneling, Chisel, Ligolo-ng |
| **SOC Operations** | Alert Triage, Log & Traffic Analysis, Incident Reporting |
| **Assessment & Scripting** | CVSS v3.1, Python, C, PowerShell |

### Tools

**Pentesting:** Burp Suite · SQLMap · ffuf · Nmap · Metasploit · NetExec · Impacket · Responder · Wireshark

**Active Directory & Post-Exploitation:** BloodHound · PowerView · Mimikatz · Rubeus · Evil-WinRM · Hashcat

**SOC / SIEM:** Stellar Cyber Open XDR · Elastic SIEM

---

## Selected Projects

### 1. Web Application Vulnerability Reports — Yavuzlar Lab

Practical vulnerability research documented in structured pentest reports.

- **IDOR — Free Purchase via OTP Bypass:** Exploited a purchase-flow logic weakness. CVSS v3.1: **7.5 (High)**
- **Command Injection — Ping Feature Filter Bypass:** Demonstrated RCE through input-filter bypass. CVSS v3.1: **9.8 (Critical)**
- Reports include technical analysis, proof of concept, business impact, risk assessment, and remediation.

**[View Writeups](https://github.com/dewafanii/cyber-writeups)**

---

### 2. SQL Injection Risk Analysis — Undergraduate Thesis

Black-box penetration test against a Docker-based vulnerable web application.

- Identified authentication bypass and SQL Injection vulnerabilities.
- Demonstrated UNION-based and Time-Based Blind SQL Injection.
- Extracted 15 user credential records in the test environment.
- Risk assessed using CVSS v3.1: **7.5 (High)**

---

### 3. C-Based Windows Loader — Educational Research

- Developed a proof-of-concept Windows loader in C for controlled lab research.
- Explored Windows API usage, process injection, and basic AV evasion techniques.
- Published a technical write-up on Medium.

**[View Writeup](https://medium.com/@reinaldy.thendean3/offensive-security-engineering-a-step-by-step-poc-for-bypassing-windows-defender-using-a-custom-c-5b66b2cbe984)**

---

### 4. Active Directory Penetration Test — HTB Academy Lab

End-to-end internal AD pentest documented from unauthenticated recon to full domain compromise.

- Chained 5 techniques: LLMNR poisoning → plaintext creds in SMB share → MSSQL `xp_cmdshell` + `SeImpersonatePrivilege` abuse → BloodHound-mapped `GenericAll` ACL abuse → DCSync.
- Extracted `krbtgt` hash (Golden Ticket pre-requisite), confirming full domain compromise of `INLANEFREIGHT.LOCAL`.
- Write-up includes attack path diagram, per-phase impact analysis, root cause analysis, and defender remediation notes.

**[View Writeup](https://github.com/dewafanii/Active-Directory-Writeups)**

---

## Professional Experience

### SOC Level 1 Analyst Intern
**PT. Sembilan Pilar Semesta** · August 2025 – February 2026

- Monitored security alerts and network traffic using Stellar Cyber and Elastic SIEM across two financial-sector client sites.
- Triaged approximately **20 alerts per day** and escalated **10 confirmed incidents**.
- Analyzed logs for suspicious activity and attack patterns; prepared incident reports for escalation.

---

## Certifications & Training

- **Certified Ethical Hacker (CEH)** — EC-Council / Course-Net
- **Web Pentest Level 1** — JadiHacker
- **Python for Hacking & Basic Web Pentesting** — ITBox
- **Currently Learning:** Hack The Box CPTS Path

---

## Education

### Bachelor of Information Technology
**Universitas Multimedia Nusantara** · 2022 – 2026

- GPA: **3.82/4.00**
- Thesis: *Analisis Risiko SQL Injection pada Aplikasi Web Menggunakan CVSS v3.1*
- Focus: Web Application Security · Penetration Testing · Network Security

---

*Open to Junior Penetration Tester opportunities.*
