# Attack Path Lab – From Reconnaissance to Privilege Escalation

## Overview

This project simulates a real-world penetration testing scenario in a controlled lab environment. The objective was to identify potential attack paths from initial reconnaissance to privilege escalation on a Linux server.

The lab demonstrates how exposed services, authentication weaknesses, and privilege misconfigurations can lead to full system compromise.

This project highlights both offensive security techniques and defensive awareness.

---

## Objectives

- Perform reconnaissance and host discovery
- Enumerate exposed services
- Simulate brute-force authentication attempts
- Analyze system logs for attack traces
- Identify privilege escalation vectors
- Document findings in a professional penetration testing report

---

## Lab Environment

### Target Machine
- Ubuntu Server
- OpenSSH service enabled
- Standard user account with sudo privileges

### Attacker Machine
- Kali Linux
- Tools used: Nmap, SSH, Linux enumeration commands

### Network
- Internal virtual LAN environment

---

## Methodology

The assessment followed a structured penetration testing methodology:

1. Reconnaissance
2. Enumeration
3. Exploitation Simulation
4. Log Analysis
5. Privilege Escalation Assessment
6. Risk Evaluation
7. Reporting

---

## Key Findings

- SSH service exposed to the network
- Multiple failed authentication attempts observed
- User account configured with full sudo privileges
- Presence of SUID binaries that may enable privilege escalation

Overall Risk Level: **High**

---

## Repository Structure

attack-path-lab/
│
├── recon/ → Host discovery results
├── enumeration/ → Service analysis outputs
├── exploitation/ → Authentication attempt logs
├── privesc/ → Privilege escalation findings
├── screenshots/ → Evidence from each phase
├── report/ → Final penetration testing report
└── notes/ → Research and observations


---

## Skills Demonstrated

- Network reconnaissance
- Service enumeration
- Linux system analysis
- Log analysis
- Privilege escalation assessment
- Risk evaluation
- Technical reporting
- Documentation and evidence collection

---

## Tools Used

- Nmap
- SSH
- Linux command-line tools
- System logs
- Ubuntu Server
- Kali Linux

---

## Key Learning Outcomes

This project demonstrates:

- How attackers identify entry points
- The importance of monitoring authentication attempts
- Risks of excessive sudo privileges
- The role of proper system hardening
- How to document findings professionally

---

## Disclaimer

This project was conducted in a controlled lab environment for educational purposes only. No real systems were targeted.

---

## Author

**Wassim Abelghouch**  
Cybersecurity Student & Aspiring Penetration Tester
