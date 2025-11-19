🔐 Vulnerability Assessment & Penetration Testing (VAPT)
Target Machine: Metasploitable2 | Attacker Machine: Kali Linux

This project demonstrates a complete end-to-end penetration test on the Metasploitable2 vulnerable machine using industry-standard VAPT methodology.
It includes reconnaissance, vulnerability scanning, exploitation, post-exploitation, and reporting.

📌 Project Overview

Metasploitable2 is a deliberately insecure Linux system widely used for practicing penetration testing techniques.
This project simulates a real-world penetration test to identify and exploit vulnerabilities.

Objectives

Perform full network & service enumeration

Identify critical vulnerabilities

Exploit high-impact services

Gain shell access & escalate privileges

Document findings with mitigation steps

🧪 Lab Environment
Component	Details
Attacker	Kali Linux
Target	Metasploitable2
Network	Host-only / NAT / Internal
IP Scheme Used	192.168.***.***/24

Example Setup

Kali Linux        → 192.168.***.***
Metasploitable2   → 192.168.***.***

🛠 Tools Used

Nmap

Nikto

Metasploit Framework

Searchsploit

Enum4linux

Hydra

Netcat

Burp Suite (optional)

📡 VAPT Methodology
1. Reconnaissance

Nmap host discovery

Port and service scanning

OS detection

2. Vulnerability Assessment

Service version checks

Nikto web vulnerability scan

Mapping known CVEs

3. Exploitation

Exploited vulnerabilities:

Service	Vulnerability	Impact

FTP (21)	vsftpd 2.3.4 Backdoor	Root shell

HTTP (8180)	Tomcat Manager RCE	Remote WAR upload

SMB (445)	Misconfigured Samba	Local user shell

4. Post-Exploitation

User enumeration

Password dumping

Privilege escalation using SUID/weak configs

Persistence creation

5. Reporting
Full professional report included in the repository.

📄 Included Files & Structure
VAPT-Metasploitable2/
│── README.md
│── Report.pdf
│── /scan_results
│   ├── nmap.txt
│── /exploits
│── /images

📘 Key Findings (Summary)

Vulnerability	Severity	Result

VSFTPD Backdoor	Critical	Instant root access

Tomcat Manager Weak Auth	High	Full server compromise

Samba Misconfiguration	High	Local user shell


Mitigation steps are included in Report.pdf.

🏁 Conclusion

This project demonstrates:

Real-world penetration testing workflow

Ability to perform reconnaissance & exploitation

Practical skills in Metasploit & manual techniques

Strong reporting & documentation abilities

⭐ Author

Sonu Choursiya
Cybersecurity Intern | Offensive Security Learner

