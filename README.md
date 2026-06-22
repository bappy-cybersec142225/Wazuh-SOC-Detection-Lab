# Wazuh-SOC-Detection-Lab
<img width="1280" height="714" alt="SOC LAB" src="https://github.com/user-attachments/assets/f07e94e3-db70-4bbd-b646-68a33068b5d5" />

### Threat Monitoring, Detection Engineering, and Attack Simulation with Wazuh, Sysmon, and Atomic Red Team
(https://documentation.wazuh.com/current/installation-guide/index.html)

This project is designed as a professional cybersecurity portfolio demonstrating:

* SIEM Deployment
* Threat Detection Engineering
* Security Monitoring
* MITRE ATT&CK Mapping
* Adversary Emulation
* Incident Investigation
* Threat Hunting

---

# Phase 1: Project Planning

## Project Objectives

Build a complete SOC lab capable of:

✅ Collecting Windows Security Events

✅ Monitoring Sysmon Telemetry

✅ Simulating Attacks

✅ Detecting Adversary Behaviors

✅ Generating Alerts

✅ Mapping Activities to MITRE ATT&CK

---

## Final Architecture

```text
Windows 11 Endpoint
│
├── Sysmon
├── InjectProc
└── Wazuh Agent
        │
        ▼
Ubuntu Server
│
├── Wazuh Manager
├── Wazuh Indexer
├── Wazuh Dashboard
└── Filebeat
        │
        ▼
Detection & Monitoring
        │
        ▼
MITRE ATT&CK Mapping
```

---

# Phase 2: Create GitHub Repository

Create Repository

```text
wazuh-soc-detection-lab
```

Repository Description

```text
Threat Monitoring, Detection Engineering, and Attack Simulation with Wazuh, Sysmon, and Atomic Red Team.
```

Topics

```text
wazuh
soc
siem
sysmon
InjectProc
mitre-attck
detection-engineering
threat-hunting
cybersecurity
security-monitoring
ubuntu
windows11
```

---

# Phase 3: Project Structure

Create folders

```text
wazuh-soc-detection-lab/
│
├── README.md
│
├── configs/
│   ├── sysmon/
│   ├── wazuh/
│   └── windows-agent/
│
├── InjectProc/
│
├── detections/
│
├── reports/
│
├── Screenshots/
│
└── LICENSE
```

---

# Phase 4: Lab Setup Documentation

Create:

```text
docs/installation/
```

Add:

## 01-Ubuntu-Installation.md

Contents:

* VirtualBox Setup
* Ubuntu Installation
* Network Configuration

---

## 02-Wazuh-Installation.md

Contents:

* Wazuh Manager
* Indexer
* Dashboard

Installation commands

---

## 03-Windows-Agent.md

Contents:

* Windows 11 Setup
* Agent Installation
* Registration

---

## 04-Sysmon-Installation.md

Contents:

* Sysmon Installation

---

## 05-InjectProc

Contents:

* Installation
* Test Execution

---

# Phase 5: Create Architecture Documentation

Create:

```text
docs/architecture/lab-architecture.md
```

Include

## Network Diagram

```text
Windows 11 VM
        │
        ▼
Wazuh Agent
        │
        ▼
Wazuh Manager
        │
        ▼
Indexer
        │
        ▼
Dashboard
```

---

# Phase 6: Create Detection Engineering Section

Folder

```text
detections/
```

Create:

## powershell-detection.md

Technique

```text
T1059.001
```

Description

```text
PowerShell execution detection using Sysmon Event ID 1.
```

---

## credential-access.md

Technique

```text
T1003
```

Description

```text
Credential Dumping Detection
```

---

## discovery.md

Technique

```text
T1082
```

Description

```text
System Information Discovery
```

---

# Phase 7: InjectProc

The InjectProc tool and payload (hello-world-x64.dll) were downloaded and placed in a dedicated working directory.

```
C:\Users\fazleh\Downloads\DLLInjection\InjectProc.exe

C:\Users\fazleh\Downloads\DLLInjection\hello-world-x64.dll

```text
```

Expected Alerts

```text
System Information Discovery
```

---

# Phase 8: Screenshots Collection

Create

```text

Capture screenshots for:

### Infrastructure

```text
01-VirtualBox-Lab.png
02-Ubuntu-Server.png
03-Windows11.png
```

### Wazuh

```text
04-Wazuh-Dashboard.png
05-Agent-Connected.png
06-Security-Events.png
```

### Sysmon

```text
07-Sysmon-Service.png
08-Sysmon-Logs.png
```

### Atomic Red Team

```text
09-Atomic-Test-T1059.png
10-Atomic-Test-T1003.png
11-Atomic-Test-T1082.png
```

### Detection

```text
12-PowerShell-Detection.png
13-Credential-Dump-Detection.png
14-Discovery-Detection.png
15-MITRE-Mapping.png
```

# Phase 9: Create Detection Reports

Folder

```text
reports/
```

Create

## Attack-Simulation-Report.md

Structure

```text
Objective
Tools Used
Attack Simulation
Observed Events
Detection Analysis
MITRE Mapping
Recommendations
```

---

# Phase 10: Professional README Sections

README Structure

```text
1. Project Overview
2. Objectives
3. Architecture
4. Technologies Used
5. Lab Environment
6. Installation Guide
7. Sysmon Configuration
8. InjectProc
9. Detection Engineering
10. MITRE ATT&CK Mapping
11. Screenshots
12. Lessons Learned
13. Future Improvements
14. References
15. Author
```

---

# Phase 11: GitHub Portfolio Enhancements

Add:

### Badges

```markdown
![Wazuh](https://img.shields.io/badge/Wazuh-SIEM-blue)

![Sysmon](https://img.shields.io/badge/Sysmon-Monitoring-green)

![MITRE](https://img.shields.io/badge/MITRE-ATT%26CK-red)

![Atomic Red Team](https://img.shields.io/badge/Atomic-RedTeam-orange)
```

---

# Phase 12: Future Enhancements

Roadmap

```text
☐ Sigma Rules Integration
☐ Suricata IDS Integration
☐ Splunk Integration
☐ YARA Malware Detection
☐ Velociraptor DFIR
☐ Active Directory Monitoring
☐ SOAR Automation
☐ Threat Intelligence Feeds
```

---

# Final Deliverable

By completing this project, your GitHub repository will showcase:

* SIEM Engineering
* SOC Operations
* Threat Detection
* Threat Hunting
* MITRE ATT&CK
* Windows Log Analysis
* Sysmon Telemetry
* Atomic Red Team Testing
* Incident Investigation
* Wazuh Administration

TDeveloped and Maintained by

Bappy Sharma
CISA | FMVA | CBCA
Cybersecurity Enthusiast | IT Auditor | Banking Professional
