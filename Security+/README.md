# Security+ Study Notes

> A structured collection of personal cybersecurity notes covering Security+ topics, from social engineering to risk management.

## 📖 Overview

This repository hosts detailed study notes for Security+ organized into major topic areas. Use it as a reference or study guide to reinforce key concepts and terminology.

---

## 📑 Table of Contents

1. [Social Engineering](#social-engineering)  
2. [Malware Threat Vectors](#malware-threat-vectors)  
3. [Unauthorized Access](#unauthorized-access)  
4. [Password Attacks](#password-attacks)  
5. [Physical Security Threats](#physical-security-threats)  
6. [Third-Party Attacks](#third-party-attacks)  
7. [Web Vulnerabilities (XSS, CSRF)](#web-vulnerabilities-xss-csrf)  
8. [Network-Based Attacks](#network-based-attacks)  
9. [Vulnerability Scanners](#vulnerability-scanners)  
10. [Honeypots & Honeynets](#honeypots--honeynets)  
11. [Penetration Testing Methodologies](#penetration-testing-methodologies)  
12. [Data Protection Techniques](#data-protection-techniques)  
13. [Virtualization & Hypervisors](#virtualization--hypervisors)  
14. [Cloud Computing & Redundancy](#cloud-computing--redundancy)  
15. [Cryptography & Hashing](#cryptography--hashing)  
16. [Public Key Infrastructure (PKI)](#public-key-infrastructure-pki)  
17. [Common Protocols & Ports](#common-protocols--ports)  
18. [Secure Network Design](#secure-network-design)  
19. [Firewalls, Proxies, IDS/IPS](#firewalls-proxies-idsips)  
20. [VPNs & Tunneling](#vpns--tunneling)  
21. [Bluetooth Security](#bluetooth-security)  
22. [Authentication Protocols (Kerberos)](#authentication-protocols-kerberos)  
23. [Indicators of Compromise & Attack](#indicators-of-compromise--attack)  
24. [Metadata & Forensics](#metadata--forensics)  
25. [Cyber Kill Chain](#cyber-kill-chain)  
26. [Information Security Risk Management](#information-security-risk-management)  

---

## 🔍 Social Engineering

- **Phishing**, **Spear Phishing**, **Whaling**  
- **Vishing**, **Smishing**, **SPIM**, **Bluejacking**  
- **Tailgating**, **Dumpster Diving**, **Piggybacking**  
- Psychological principles: Authority, Intimidation, Consensus, Scarcity, Familiarity, Trust, Urgency  

---

## 🦠 Malware Threat Vectors

- **Viruses**, **Worms**, **Trojans**, **RATs**  
- **PUPs/PUAs**, **Backdoors**, **Botnets**, **Rootkits**  

---

## 🔓 Unauthorized Access

- **Backdoors**, **Botnets**, **Rootkits**  

---

## 🔑 Password Attacks

- **Dictionary**, **Brute‑Force**, **Hybrid**, **Rainbow‑Table**  
- Tools: **Hydra** (syntax examples included)  

---

## 🛡 Physical Security Threats

- **Malicious USB Cables** (BadUSB/Rubber Ducky)  
- **Flash‑drive exploits**, **Card cloning**, **Skimming**  

---

## 🌐 Third-Party Attacks

- **Supply chain**, **Cloud-based**, **Poorly written APIs**  

---

## 💻 Web Vulnerabilities (XSS, CSRF)

- **Cross‑Site Scripting (XSS)** injection vectors and defenses  
- **Cross‑Site Request Forgery (CSRF)** mechanics and mitigation  

---

## 🌐 Network‑Based Attacks

- **Fuzzing**, **Port scans** (including Xmas scans)  
- **Man‑in‑the‑Middle** (passive sniffing vs. active session hijack)  
- **IP/MAC/Email/Caller‑ID spoofing**, **Smurf Attacks**  

---

## 🔍 Vulnerability Scanners

- Tools: **Nikto**, **Nessus**, **OpenVAS**, **Qualys**, **Rapid7 Nexpose**  

---

## 🎯 Honeypots & Honeynets

- **Honeypots** (purpose, pseudo‑flaws)  
- **Honeynet** collections  

---

## 🪓 Penetration Testing Methodologies

- **Black‑box**, **Grey‑box**, **White‑box**  
- **Blind tests**, **Target tests**  

---

## 🔒 Data Protection Techniques

- **Masking**, **Obfuscation**, **Anonymization**, **Tokenization**  
- **BitLocker** full‑disk encryption  

---

## 🖥 Virtualization & Hypervisors

- **Type 1 (bare‑metal)** vs. **Type 2 (hosted)** hypervisors  
- Risks & security considerations  

---

## ☁️ Cloud Computing & Redundancy

- **IaaS/PaaS/SaaS** fundamentals  
- **Redundancy** (UPS, RAID, failover)  

---

## 🔐 Cryptography & Hashing

- **Symmetric** (block vs. stream ciphers)  
- **Asymmetric** (public vs. private key)  
- **Hash algorithms**: MD5, SHA‑1, SHA‑2 family  
- **Hybrid cryptography** concepts  

---

## 🏛 Public Key Infrastructure (PKI)

- **Digital certificates**, **Certificate Authorities (CAs)**  
- **Non‑repudiation**, **digital signatures**  

---

## 📡 Common Protocols & Ports

| Protocol | Port(s)        | Notes                                           |
|----------|----------------|-------------------------------------------------|
| FTP      | 20, 21         | Plaintext; use FTPS/SFTP for encryption         |
| SSH      | 22             | Secure remote access; `scp` for file transfer   |
| Telnet   | 23             | Deprecated; plaintext                          |
| SMTP     | 25, 465, 587   | Email transit                                  |
| DNS      | 53             | UDP/TCP                                       |
| DHCP     | 67, 68         | Dynamic IP assignment                          |
| HTTP     | 80             | Plaintext; use HTTPS (443)                     |
| POP3     | 110, 995       | Email retrieval; POP3S for SSL/TLS             |
| IMAP     | 143, 993       | Email sync; IMAPS for SSL/TLS                  |
| RDP      | 3389           | Windows remote desktop                         |
| LDAP     | 389, 636       | Directory services; LDAPS for SSL/TLS          |
| RADIUS   | 1812, 1813     | AAA (authentication, accounting)                |
| NTP      | 123            | Time synchronization                            |

---

## 🔐 Secure Network Design

- **Hubs**, **Switches**, **Routers**, **VLANs**  
- **NAT** vs. **PAT** (port address translation)  

---

## 🔥 Firewalls, Proxies, IDS/IPS

- **Packet‑filtering**, **Stateful**, **Application‑level**, **Next‑Gen**, **Cloud‑based**  
- **Forward** vs. **Reverse proxies**  
- **IDS** (NIDS/HIDS) vs. **IPS**  

---

## 🛡 VPNs & Tunneling

- **VPN types**, **tunneling protocols**, encryption use cases  

---

## 📶 Bluetooth Security

- Attacks: **Bluejacking**, **Bluesnarfing**, **Bluebugging**  

---

## 🔑 Authentication Protocols (Kerberos)

- **SSO**, **ticketing**, **timestamp-based replay protection**  

---

## ⚠ Indicators of Compromise & Attack

- **IOCs** (e.g., unusual logins, malware detections)  
- **IOAs** (behavior‑based detection)  

---

## 📊 Metadata & Forensics

- **File**, **email**, **web**, **mobile** metadata use in investigations  

---

## 🔗 Cyber Kill Chain

1. Reconnaissance  
2. Weaponization  
3. Delivery  
4. Exploitation  
5. Installation  
6. Command & Control  
7. Actions on Objectives  

---

## 🎯 Information Security Risk Management

- Risk identification, assessment, treatment, monitoring  
- Key terms: Asset, Vulnerability, Threat, Exploit, Controls, Residual risk  

---

## 🛠 Usage

1. Clone this repo  
2. Browse notes by folder/topic  
3. Use them for study, reference, or to build flashcards  

---

## 🤝 Contributing

Feel free to submit pull requests with updates, clarifications, or new examples!

---

## 🔗 References

- Notion: [Cross-Site Scripting (Hackers Handbook)](https://www.notion.so/XSS-Cross-Site-Scripting-Hackers-Handbook-1-22703ee046f580fb8eb0d9d389688898?pvs=21)  
