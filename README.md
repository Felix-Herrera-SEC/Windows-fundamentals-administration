# 🪟 Windows Fundamentals & Administration — SOC Analyst Portfolio

## Overview

This repository documents a series of 10 hands-on Windows administration and security labs designed to develop practical skills relevant to a Security Operations Center (SOC) Analyst Tier 1 role.

The labs focus on understanding Windows operating system architecture, user accounts, access controls, processes, services, networking, PowerShell, endpoint security, and persistence mechanisms.

Each lab combines technical exercises with security analysis to demonstrate how Windows administrative knowledge supports endpoint investigations, security alert triage, and incident response.

**Focus:** Windows Administration | Endpoint Security | SOC Operations  
**Difficulty:** Beginner to Intermediate  
**Total Labs:** 10  
**Status:** In Progress

---

## Objectives

The primary objectives of this section are to:

- Understand Windows architecture and core operating system components.
- Manage and investigate local user accounts, groups, and permissions.
- Analyze Windows processes, services, and system activity.
- Examine the Windows file system and Registry.
- Investigate network connections using native Windows tools.
- Develop practical command-line and PowerShell skills.
- Understand Microsoft Defender and Windows Firewall.
- Identify common Windows persistence mechanisms.
- Explore remote administration and access security.
- Conduct an endpoint security investigation using Windows administrative tools.

---

## Lab Environment

| Component | Technology |
|---|---|
| Host Operating System | Windows |
| Virtualization | Oracle VirtualBox |
| Guest Operating System | Windows 11 |
| Network Configuration | NAT |
| Command-Line Tools | Command Prompt, PowerShell |
| Administrative Tools | Task Manager, Services, Registry Editor, Event Viewer |
| Security Tools | Microsoft Defender, Windows Firewall |
| Investigation Tools | Microsoft Sysinternals |
| Documentation | GitHub, Markdown, Screenshots |

All security-related exercises are conducted in an authorized lab environment.

---

## Tools & Technologies

**Windows Administration**
- Task Manager
- Computer Management
- Services Console
- Registry Editor
- Task Scheduler
- Local Users and Groups
- Windows Event Viewer

**Command-Line & Scripting**
- Command Prompt (CMD)
- Windows PowerShell
- Windows networking utilities
- Windows management commands

**Endpoint Security**
- Microsoft Defender Antivirus
- Windows Defender Firewall
- Windows Security
- Microsoft Sysinternals Suite
- Process Explorer
- Autoruns
- TCPView

**Virtualization**
- Oracle VirtualBox
- Windows 11 virtual machine




## Investigation Methodology

The labs follow a consistent methodology aligned with entry-level SOC responsibilities.

### 1. Establish a Baseline

Identify expected Windows system behavior, including legitimate processes, services, accounts, and network connections.

### 2. Collect Evidence

Use Windows administrative tools, PowerShell, and Sysinternals to collect relevant system information.

### 3. Analyze System Activity

Investigate processes, user privileges, services, file system changes, Registry entries, and network connections.

### 4. Identify Security-Relevant Findings

Determine whether observed activity is expected, unusual, misconfigured, or potentially suspicious.

### 5. Document and Report

Record observations, supporting evidence, limitations, and recommended next steps.

This methodology emphasizes evidence-based analysis rather than assuming that unusual activity is malicious.

---

## SOC Analyst Relevance

Windows endpoints are a common source of security telemetry in enterprise environments.

Understanding Windows administration enables SOC analysts to investigate alerts involving:

| Security Scenario | Relevant Windows Skills |
|---|---|
| Suspicious process execution | Task Manager, Process Explorer, PowerShell |
| Unauthorized account activity | Local users, groups, permissions |
| Privilege escalation indicators | UAC, administrator groups, access controls |
| Suspicious network connections | netstat, TCPView, PowerShell |
| Malware persistence | Registry, scheduled tasks, startup entries |
| Endpoint security alerts | Microsoft Defender, Windows Security |
| Unauthorized remote access | RDP, remote administration, firewall |
| System configuration changes | Services, Registry, administrative tools |

These skills provide a foundation for more advanced Windows Event Log analysis, Active Directory investigations, SIEM monitoring, and endpoint detection and response.

---

## Evidence & Documentation Standards

Each lab will include:

- Clear objectives and technical scope.
- Description of the lab environment.
- Tools and commands used.
- Step-by-step procedures.
- Screenshots of completed exercises.
- Observed results and technical explanations.
- SOC relevance and security implications.
- Lessons learned.

Screenshots and reports will be based on actual lab results. Simulated security incidents will be explicitly labeled.

Sensitive information, credentials, and unnecessary personal data will be excluded from published evidence.

---

## Expected Learning Outcomes

Upon completing this section, I aim to demonstrate the ability to:

1. Navigate and administer Windows systems using graphical and command-line tools.
2. Identify and investigate Windows processes and services.
3. Evaluate local accounts, permissions, and security configurations.
4. Analyze Windows network connections and troubleshoot connectivity.
5. Use PowerShell to collect endpoint investigation data.
6. Understand common Windows persistence techniques.
7. Review endpoint protection and firewall configurations.
8. Conduct a structured Windows endpoint investigation.
9. Document technical findings in a professional SOC-style report.

---

## Related Portfolio Sections

This repository is part of a broader SOC Analyst Tier 1 training portfolio.

- **Section 01:** Linux Fundamentals
- **Section 02:** Networking Fundamentals
- **Section 03:** Wireshark & Packet Analysis
- **Section 04:** Windows Fundamentals & Administration — Current Section
- **Section 05:** Active Directory Fundamentals
- **Section 06:** Windows Logs & Event Viewer
- **Section 07:** SIEM & Log Analysis
- **Section 08:** EDR & Endpoint Security
- **Section 09:** Phishing & Email Analysis
- **Section 10:** SOC Alert Triage & Incident Investigation
- **Section 11:** MITRE ATT&CK & Threat Analysis
- **Section 12:** SOC Analyst Capstone Projects

---

## Professional Development Focus

This section supports my preparation for entry-level cybersecurity positions, particularly:

- SOC Analyst Tier 1
- Junior Security Analyst
- Cybersecurity Analyst I
- Security Operations Analyst
- Junior Incident Response Analyst

The emphasis is on developing practical, demonstrable technical skills and documenting the investigative reasoning behind each exercise.

---

## Disclaimer

All exercises are intended for educational purposes and are performed on systems owned by or explicitly authorized for testing.

Any suspicious activity or security incident described as a simulation is not presented as a real-world compromise.

---

**Next Milestone:** Lab 01 — Windows Operating System Fundamentals
