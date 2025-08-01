# -Samuel-N.-Cybersecurity-Engineer-Security+-AWS-Security-Fortinet-FCA-
Cybersecurity professional with Security+, AWS, Microsoft SC-900, and Fortinet FCA certifications. I specialize in network security, vulnerability assessments, risk management, cloud security, web application testing, and IT operations.

#  🔐 Cybersecurity & Cloud Projects
# Windows-Firewall-Security-Configuration-With-Kali-Linux-Attack-Simulation
- Configured Windows Defender Firewall inbound rules to allow essential traffic (HTTP/HTTPS) while blocking ICMP to prevent ping-based reconnaissance from Kali Linux.
- Simulated real-world attack (Nmap scan & ping test) from Kali guest machine to confirm firewall effectiveness—logged dropped packets and verified that unauthorized access     attempts were blocked.

# Port-Service-Security-Audit-Using-Nmap-and-CMD
- Identified used and unused ports, then disabled unnecessary services running on Windows using CMD and Nmap to reduce attack surface and improve system security.
- Blocked vulnerable ports using Windows Firewall rules after scanning with Nmap and inspecting active connections via netstat to ensure only essential services remain open.

# Network-Security-Hardening-Using-Wireshark
- Used Wireshark to capture and analyze baseline network traffic on Windows 11, identifying potential misconfigurations, scanning attempts, and unencrypted transmissions.
- Implemented security hardening by enabling HTTPS settings and DNS filtering, then verified results by comparing post-hardening traffic captures—showed clear reduction in    insecure behavior.
  
# AWS-IAM-User-Secure-Setup-Project
- Created and configured IAM user with assigned managed policies, grouped roles, and enforced Multi-Factor Authentication (MFA) using Microsoft Authenticator to secure AWS    access.
- Applied security best practices such as least privilege principle, avoiding root account use, and verifying MFA functionality through practical sign-in test.

# Burp-Proxy-For-Web-Traffic-Dissection-And-Security-Hardening
- Utilized Burp Suite to intercept, analyze, and manipulate HTTP/HTTPS web traffic on a Windows machine—tested input fields, cookies, and responses for vulnerabilities        like <script>, SQL syntax, and status code anomalies.
- Configured proxy and browser settings to route traffic through Burp Proxy, enabling hands-on vulnerability testing and applying hardening techniques to improve web          application security posture.
  

  # Installation-and-Configuring-of-Metasploit-framework-on-Kali-Linux
  - Installed and configured Metasploit Framework on Kali Linux using package manager and validated PostgreSQL database connectivity to enable exploit testing environment.
  - Initiated Metasploit console and database setup (msfdb init, db_connect, db_status) to prepare for structured vulnerability validation and penetration testing               activities.
 
 # Creating-and-Managing-Workspace-In-The-Metasploit-framework-On-Kali-Linux-to-Organize-Scan-Result-
- Configured and managed Metasploit workspaces on Kali Linux to organize scan results across multiple targets—used workspace commands to add, rename, delete, and isolate      project activities.
- Initialized Metasploit database and verified PostgreSQL connectivity; added hosts to each workspace using db_nmap for structured penetration test tracking.

# Using-The-Metasploit-Console
- Launched Metasploit Console on Kali Linux to simulate attacker behavior and strengthen system defenses through proactive vulnerability identification.
- Applied port scanning modules (search portscan) for network reconnaissance and targeted auxiliary scans using set RHOST <IP> to enhance data precision.
- Searched CVE-specific exploits (search cve:<year>) within Metasploit for vulnerability validation and payload selection.
- Accessed and configured payloads (show payload, search type payload name:ssh) to prepare relevant attack vectors and test countermeasures.

# Port-Scanning-and-Enumeration-on-Metasploit
-Performed root-level Nmap scan with service and OS detection (nmap -sS -sV -O) and exported results in XML format for structured analysis.
- Initialized Metasploit database (msfdb init) and launched console (msfconsole) for integration of external scan results.
- Created and accessed custom workspace to isolate scan data, imported Nmap XML (db_import M1) for host enumeration and vulnerability mapping.
- Used Metasploit’s built-in modules (host, db_nmap) to analyze hosts and conduct follow-up scans within workspace environment.

# Using-Auxiliary-Modules-on-Metasploit
- Demonstrated use of Metasploit Auxiliary Modules for threat detection by initiating scans for TCP ports and FTP version enumeration within an isolated workspace (search     portscan, search ftp_version, set RHOSTS, run).
- Started Metasploit environment (msfconsole, msfdb init) and created workspace to organize scanning results and streamline workflow.
- Shared mitigation strategies against reconnaissance attacks using auxiliary modules, including firewall hardening, segmentation, honeypots, service obfuscation, and         active threat hunting protocols.











