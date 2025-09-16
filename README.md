# CyberSecurity_learning_notes001

# Topics to Cover

1. Networking fundamentals (OSI & TCP/IP)
2. IP addressing & subnetting
3. Common protocols (HTTP, HTTPS, DNS, SMTP, FTP, SSH)
4. Ports and port scanning
5. TCP/UDP internals and handshakes
6. Packet analysis with Wireshark
7. Network topologies and segmentation
8. Firewalls (stateful vs stateless)
9. VPNs and secure tunnels
10. IDS vs IPS concepts
11. Routing protocols & BGP basics
12. Wireless security (WPA2/WPA3, 802.11)
13. Linux fundamentals for security
14. Windows internals & hardening
15. Command-line essentials (Bash, PowerShell)
16. User and privilege management
17. Authentication methods (MFA, SSO, OAuth)
18. Password policies and cracking techniques
19. Public Key Infrastructure (PKI) & certificates
20. Cryptography basics (symmetric/asymmetric)
21. Hashing algorithms & integrity checks
22. TLS/SSL and HTTPS mechanics
23. Secure key management
24. Vulnerability assessment process
25. Common vulnerability types (buffer overflow, RCE)
26. Exploit development concepts
27. Metasploit framework basics
28. Reconnaissance & OSINT techniques
29. Port scanning with Nmap
30. Web application attacks (OWASP Top 10)
31. SQL Injection deep dive
32. Cross-Site Scripting (XSS) variants
33. CSRF and SameSite mitigation
34. Server-side request forgery (SSRF)
35. Directory traversal & file inclusion attacks
36. Web app security testing with Burp Suite
37. API security (REST, GraphQL)
38. Secure coding principles (input validation, output encoding)
39. Static code analysis and SAST tools
40. Dynamic analysis and DAST tools
41. Container security (Docker)
42. Kubernetes security fundamentals
43. Cloud security fundamentals (shared responsibility)
44. AWS security basics (IAM, VPC, KMS)
45. Azure & GCP security essentials
46. Identity and Access Management (IAM) design
47. Endpoint protection and EDR concepts
48. Malware types & lifecycle (trojans, ransomware, worms)
49. Malware analysis basics (static & dynamic)
50. Reverse engineering fundamentals (IDA, Ghidra)
51. Memory forensics basics (Volatility)
52. Disk forensics and file carving
53. Incident response lifecycle & playbooks
54. Digital evidence collection & chain of custody
55. SIEM fundamentals (log collection, correlation)
56. Log analysis best practices
57. Threat intelligence (TTPs, IOCs)
58. Threat hunting methodologies
59. Red teaming vs penetration testing
60. Social engineering techniques & defense
61. Phishing attack mechanics & simulation
62. Physical security principles & attacks
63. Risk assessment frameworks (NIST, ISO 27001)
64. Security policies, standards, and governance
65. Vulnerability disclosure & bug bounty programs
66. Secure DevOps / DevSecOps practices
67. CI/CD pipeline security
68. Application hardening & runtime protections
69. Code signing and supply-chain security
70. Secure architecture and threat modeling (STRIDE, DREAD)
71. Business continuity & disaster recovery planning
72. Backup strategies and secure storage
73. Data privacy principles & GDPR basics
74. Insider threat detection and mitigation
75. Network segmentation and microsegmentation
76. Honeypots and deception techniques
77. Anomaly detection & behavioral analytics
78. Blockchain security fundamentals
79. IoT security challenges & mitigations
80. SCADA/ICS security basics
81. Mobile application security (Android/iOS)
82. Bluetooth & NFC attack vectors
83. Quantum computing impact on cryptography
84. Secure remote work practices (Zero Trust)
85. Zero Trust architecture principles
86. Automation and scripting for security (Python)
87. Security testing frameworks & reporting
88. Writing effective incident reports and remediation plans
89. Security metrics & KPIs (MTTR, MTTD)
90. Compliance regimes (PCI-DSS, HIPAA, SOX)
91. Ethics and legal considerations in infosec
92. Security awareness training design
93. Career paths in cybersecurity (roles & expectations)
94. Certification roadmaps (CompTIA, OSCP, CISSP, etc.)
95. Building a security lab (VMs, networking, tooling)
96. Capture The Flag (CTF) practice strategies
97. Open-source security tools ecosystem
98. Threat actor profiling and attribution basics
99. Red team toolchain and operational security (OPSEC)
100. Emerging threats & future trends (AI/ML in security)
-----------------------------------------------------------------------------------------------------------------
# Topic : 1. Networking fundamentals (OSI & TCP/IP)

## 🌐 Networking Fundamentals (expanded)

### 1. **Models & Basics**

* OSI model (7 layers)
* TCP/IP model (4 layers)
* Data encapsulation & decapsulation
* Protocol Data Units (bits, frames, packets, segments)

---

### 2. **IP Addressing**

* IPv4 structure (network ID, host ID)
* IPv6 basics (why we needed it, structure)
* Subnetting (CIDR, subnet masks)
* Private vs public IPs
* NAT (Network Address Translation)

---

### 3. **Ports & Protocols**

* TCP vs UDP (handshake, reliability)
* Well-known ports (80/443 web, 22 SSH, 53 DNS, etc.)
* Common services: DNS, HTTP/S, FTP, SMTP, POP3/IMAP, SNMP
* Ephemeral/dynamic ports

---

### 4. **Routing & Switching**

* Layer 2 vs Layer 3 devices
* MAC addresses & ARP
* Switching concepts (VLANs, STP)
* Routing concepts (static vs dynamic)
* Routing protocols (RIP, OSPF, BGP basics)

---

### 5. **Wireless Networking**

* 802.11 standards (a/b/g/n/ac/ax)
* WPA2 vs WPA3 security
* Wi-Fi attacks (evil twin, deauth, WPS brute force)

---

### 6. **Network Services**

* DHCP (how devices get IPs)
* DNS (hostname resolution, DNS records, DNS poisoning)
* Proxy servers & load balancers
* VPN concepts (tunneling, protocols like IPSec, OpenVPN, WireGuard)

---

### 7. **Traffic Analysis & Tools**

* Packet capture basics (Wireshark, tcpdump)
* Netcat for testing connections
* Traceroute & pathping
* Nmap scanning fundamentals

---

### 8. **Security Concepts in Networking**

* Firewalls (stateless vs stateful, packet filtering vs NGFW)
* IDS/IPS (Snort, Suricata)
* Network segmentation (DMZs, VLANs, Zero Trust networking)
* Common network attacks:

  * ARP spoofing
  * IP spoofing
  * MAC flooding
  * DoS/DDoS basics

---


