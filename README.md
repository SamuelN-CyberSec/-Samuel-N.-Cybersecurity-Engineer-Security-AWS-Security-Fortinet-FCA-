# -Samuel-N.-Cybersecurity-Engineer-Security+ Vulnerability Assessments, Risk Management, Cloud Security, Web Application Testing,AI Systems Builder, and IT operations.
Cybersecurity professional with Security+, AWS, Microsoft SC-900, and Fortinet FCA certifications. I specialize in network security, vulnerability assessments, risk management, cloud security, web application testing,AI Systems Builder, and IT operations.

# Agentic AI Risk Whisperer | AI-Driven Risk Intelligence Platform
•	Designed and deployed an AI-powered risk assessment system aligned with enterprise cybersecurity risk frameworks
•	Implemented multi-agent analysis to evaluate risk severity, likelihood, impact, and mitigation effectiveness
•	Built structured risk scoring models supporting cyber, compliance, operational, and strategic categories
•	Integrated RESTful APIs with a structured database for persistent tracking of risk posture
•	Developed dashboard metrics including exposure scoring (0–10 scale), trend monitoring, and risk categorization
•	Engineered asynchronous processing with status polling for real-time AI evaluation workflows
•	Improved consistency of AI-generated assessments using role-based agent architecture and controlled prompt engineering

#  🔐 Cybersecurity & Cloud Projects
## 🛡️ PROFESSIONAL EXPERIENCE / PROJECTS
### SOC Operations & Threat Detection
1. Built a Cybersecurity Operations Lab with SIEM setup guides, detection rules, and incident response playbook frameworks mapped to MITRE ATT&CK
2. Simulated network attacks from Kali Linux and validated Windows Firewall rules, logging dropped packets to confirm blocked reconnaissance attempts
3. Configured and managed Metasploit workspaces on Kali Linux, executing port scans, service enumeration, and CVE-specific exploit searches
4. Performed root-level Nmap scans with service/OS detection and imported XML results into Metasploit database for structured vulnerability mapping
5. Deployed Wazuh SIEM architecture with Sigma-to-Wazuh detection rule conversions for real-time threat monitoring and alerting

### Cloud Security (AWS)
1. Created and configured IAM users with least privilege policies, managed role-based groups, and enforced MFA via Microsoft Authenticator
2. Designed a secure 3-tier AWS reference architecture with GuardDuty, CloudTrail, multi-region logging, and KMS encryption controls
3. Built an AWS Security Auditor (Python) that audits S3, IAM, Security Groups, CloudTrail, and GuardDuty configurations against CIS benchmarks
4. Implemented S3 Block Public Access, VPC segmentation, Security Group least privilege, and automated compliance checks via AWS Config
5. Applied AWS shared responsibility model principles across IAM policies, encryption at rest/transit, and multi-region logging best practices

### Vulnerability Management
1. Developed a risk-based vulnerability prioritization engine using CVSS scoring, exploit intelligence (EPSS), and asset criticality multipliers
2. Built a Python network scanner wrapper around Nmap supporting quick, full, vulnerability, OS detection, and stealth scan profiles
3. Automated scan scheduling, XML-to-JSON parsing, and structured report generation with severity breakdowns and remediation recommendations
4. Created a complete vulnerability management pipeline: discovery → scanning → detection → prioritization → remediation → verification → reporting
5. Documented SLA-based remediation workflows with critical/ high/ medium/ low prioritization matrices and compensating control strategies

### Security Automation (Python)
1. Developed a multi-format log parser (syslog, JSON, CSV, Apache, firewall) with automated format detection and IOC extraction (IPs, domains, hashes, URLs)
2. Built an enterprise alert management system that normalizes, deduplicates, enriches, and prioritizes security alerts with risk scoring and MITRE ATT&CK mapping
3. Created a reusable IOC extractor that parses security logs for indicators of compromise and outputs structured JSON for threat intelligence feeds
4. Engineered automated triage workflows with suggested response actions, severity-based priority (P1–P5), and enrichment timestamping
5. Designed script architecture with argparse interfaces, file-based I/O, and comprehensive error handling for production-ready deployment

### Security Research & Hands-On Labs
1. Used Burp Suite to intercept and analyze HTTP/HTTPS traffic, testing for XSS (<script>), SQL injection syntax, and anomalous status codes
2. Captured and analyzed baseline network traffic with Wireshark on Windows 11, identifying misconfigurations and unencrypted transmissions
3. Installed, configured, and validated Metasploit Framework with PostgreSQL database integration for organized penetration testing workflows
4. Demonstrated auxiliary module usage (port scanning, FTP enumeration) and developed mitigation strategies including firewall hardening and honeypots
5. Conducted port/service security audits using Nmap and netstat to identify unused ports and reduce attack surface via Windows Firewall rules
---
  # Installation-and-Configuring-of-Metasploit-framework-on-Kali-Linux
  1. Installed and configured Metasploit Framework on Kali Linux using package manager and validated PostgreSQL    database connectivity to enable exploit testing environment.
  2. Initiated Metasploit console and database setup (msfdb init, db_connect, db_status) to prepare for structured   vulnerability validation and penetration testing               activities.
 
 # Creating-and-Managing-Workspace-In-The-Metasploit-framework-On-Kali-Linux-to-Organize-Scan-Result-
1. Configured and managed Metasploit workspaces on Kali Linux to organize scan results across multiple targets—used workspace commands to add, rename, delete, and isolate project activities.
2. Initialized Metasploit database and verified PostgreSQL connectivity; added hosts to each workspace using db_nmap forstructured penetration test tracking.

# Using-The-Metasploit-Console
1. Launched Metasploit Console on Kali Linux to simulate attacker behavior and strengthen system defenses through proactive vulnerability identification.
2. Applied port scanning modules (search portscan) for network reconnaissance and targeted auxiliary scans using set RHOST <IP> to enhance data precision.
3.Searched CVE-specific exploits (search cve:<year>) within Metasploit for vulnerability validation and payload selection.
4.Accessed and configured payloads (show payload, search type payload name:ssh) to prepare relevant attack vectors and test countermeasures.

# Port-Scanning-and-Enumeration-on-Metasploit
1. Performed root-level Nmap scan with service and OS detection (nmap -sS -sV -O) and exported results in XML format for structured analysis.
2.Initialized Metasploit database (msfdb init) and launched console (msfconsole) for integration of external scan results.
3. Created and accessed custom workspace to isolate scan data, imported Nmap XML (db_import M1) for host enumeration and vulnerability mapping.
4. Used Metasploit’s built-in modules (host, db_nmap) to analyze hosts and conduct follow-up scans within workspace environment.

# Using-Auxiliary-Modules-on-Metasploit
1. Demonstrated use of Metasploit Auxiliary Modules for threat detection by initiating scans for TCP ports and FTP version enumeration within an isolated workspace (search     portscan, search ftp_version, set RHOSTS, run).
2.Started Metasploit environment (msfconsole, msfdb init) and created workspace to organize scanning results and streamline workflow.
3.Shared mitigation strategies against reconnaissance attacks using auxiliary modules, including firewall hardening, segmentation, honeypots, service obfuscation, andactive threat hunting protocols.

## 🛠️ TECHNICAL SKILLS

1. **SIEM & Detection:** Wazuh, Sigma rules, MITRE ATT&CK mapping, real-time alerting, IOC extraction
2. **Cloud Security:** AWS (IAM, GuardDuty, CloudTrail, S3, KMS, VPC, Lambda, Security Groups, Config)
3. **Vulnerability Assessment:** Nmap, Burp Suite, OpenVAS, Nessus, CVSS scoring, exploit intelligence
4. **Security Tools:** Kali Linux, Metasploit, Wireshark, Gobuster, John the Ripper, Windows Firewall
5. **Automation:** Python (argparse, JSON/XML processing, subprocess), Bash, Git/GitHub, Terraform (IaC)

# 🧩 Certifications
- ✅ **CompTIA Security+**
- ✅ **AWS Cloud Essentials**
- ✅ **Microsoft SC-900**
- ✅ **Fortinet Certified Associate (FCA)**
- ✅ **Elements of AI For Bussiness**- 
- ✅ **Team Essential for Designing AI Solutions**

# 📫 Contact
- 🔗 LinkedIn: (linkedin.com/in/samuel-nwokemodo )
- 🐙 GitHub: [@SamuelN-CyberSec](https://github.com/SamuelN-CyberSec)













