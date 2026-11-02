# Jesse Kuck
**Cybersecurity Student | Digital Forensics Focus | U.S. Army Veteran**

Hands-on learner building SIEM, detection engineering, and system administration skills in my own home lab. Seeking entry-level cybersecurity roles (SOC Analyst, Security Analyst, IT Security).

---

## About Me

- Pursuing a degree in Cybersecurity at **American Military University (AMU)**, with a focus on **digital forensics**
- Working toward **CompTIA Security+**
- **U.S. Army veteran**; previously held a Secret security clearance (currently inactive)
- I learn best by building: every project here runs in my own VirtualBox lab, set up and troubleshot from scratch

---

## Featured Project

### [Purple Team Lab – Wazuh SIEM + Kali + Metasploitable](https://github.com/jkuck22/purple-team-wazuh-lab)

A multi-VM lab where I deploy a SIEM, generate attacker activity, and validate that it gets detected.

- Deployed a **Wazuh 4.14** all-in-one SIEM (manager, indexer, dashboard) on Ubuntu Server
- Connected a **Kali Linux** agent and investigated real alerts (sudo/privilege escalation, user management)
- Configured **real-time File Integrity Monitoring (FIM)** and mapped alerts to compliance frameworks (PCI DSS, NIST 800-53)
- Wrote and tested a **custom detection rule** that chains off built-in rules and escalates severity from level 5 to level 10
- Managed the server over **SSH with out-of-band host key verification**
- Documented real troubleshooting: unsupported OS install, disk exhaustion, VM lockups, legacy agent incompatibility

**Tools:** Wazuh, Kali Linux, Ubuntu Server, Metasploitable 2, VirtualBox, OpenSSH

---

## Coursework Labs – Network Security, Firewalls, and VPNs

Virtual lab work completed for my AMU network security coursework.

| Lab | What I Did |
|---|---|
| **Configuring Firewall Interfaces with pfSense** | Planned the physical firewall configuration; configured and verified the WAN, LAN, and DMZ interfaces on pfSense; validated connectivity with ICMP tests and confirmed web access to a DMZ-hosted site from a remote client |
| **Designing a Secure Network Topology** | Built simple and multi-VLAN network topologies with pfSense routing and VLAN-tagged switch interfaces; validated segmentation and connectivity using ping tests and Wireshark packet captures |
| **Configuring the Windows Defender Firewall** | Diagnosed blocked access to an IIS web server, then enabled the HTTP inbound rule through both the GUI and PowerShell (`Get-NetFirewallRule`) and verified access |
| **Defending the Network from a Simulated Attack** | Ran a breach-and-attack simulation with Infection Monkey; exploited a vulnerable web server with Metasploit to gain a shell; patched the vulnerable Bash version and confirmed the exploit no longer worked; removed malicious files with antivirus |
| **Using Social Engineering Techniques to Plan an Attack** | Performed OSINT reconnaissance on a fictional target company (WHOIS, corporate officer profiles, blogs, employee social media) and analyzed targeted and reverse social engineering attack techniques |

**Tools:** pfSense, Wireshark, Metasploit, Infection Monkey, Windows Defender Firewall, PowerShell, IIS, WHOIS

---

## Other Work

- **System Administration Labs:** coursework covering Linux and Windows administration
- **Metasploitable Practice:** vulnerable-target lab work, now integrated into the Purple Team Lab

---

## Skills

| Area | Skills |
|---|---|
| **Security Monitoring** | SIEM deployment, alert triage, File Integrity Monitoring, custom detection rules |
| **Network Security** | Firewall configuration (pfSense, Windows Defender Firewall), DMZ design, VLAN segmentation, packet analysis |
| **Offensive / Testing** | Exploitation with Metasploit, breach-and-attack simulation, OSINT reconnaissance, patch validation |
| **Systems** | Linux (Ubuntu, Kali), Windows, PowerShell, VirtualBox, virtual networking |
| **Security Concepts** | Purple teaming, social engineering, compliance mapping, SSH/host key verification, Linux permissions |
| **Tools** | Wazuh, pfSense, Wireshark, Metasploit, Infection Monkey, OpenSearch Dashboards, Git/GitHub |

---

## Currently Learning

- CompTIA Security+ exam prep
- Network security and network threats
- Cryptography concepts
- Detection engineering mapped to MITRE ATT&CK

---

## Contact

- **Email:** kuck22jesse@gmail.com
- **LinkedIn:** [linkedin.com/in/jesse-kuck22](https://www.linkedin.com/in/jesse-kuck22)
- **GitHub:** [github.com/jkuck22](https://github.com/jkuck22)
