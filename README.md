# 🛡️ Home Security Operations Center (SOC) Lab
A hands-on enterprise-style Security Operations Center built using Wazuh, Sysmon, Ubuntu Server, and Windows 11 to simulate real-world threat detection, log monitoring, incident response, and SIEM operations.

**Project Status:** 🚧 In Progress

## Current Progress

### ✅ Phase 1 - Wazuh Server Setup
- Installed Ubuntu Server
- Installed Wazuh 4.14
- Verified dashboard access
- Configured static IP

### ✅ Phase 2 - Windows Endpoint
- Installed Windows 11 Enterprise Evaluation
- Renamed endpoint to Win11-endpoint
- Installed Sysmon
- Installed Wazuh Agent
- Registered agent with Wazuh Server
- Verified endpoint connectivity

### 🔄 Current Status

The Windows endpoint successfully communicates with the Wazuh Manager.
The environment is now ready for attack simulation and log analysis.

### Upcoming

- Brute-force attack simulation
- PowerShell attack detection
- MITRE ATT&CK mapping
- Custom Wazuh detection rules
- Incident response investigation
  
## Objectives
- Build an enterprise SOC from scratch
- Deploy Wazuh SIEM
- Configure Windows endpoint monitoring
- Collect Sysmon telemetry
- Simulate cyber attacks
- Investigate alerts
- Create incident reports
- Improve detection rules
- Build a recruiter-ready cybersecurity portfolio

# Architecture

```
                 Internet
                     │
             ┌─────────────────┐
             │ Ubuntu Server    │
             │ Wazuh Manager    │
             │ SIEM             │
             └─────────────────┘
                     ▲
                     │ Agent Communication
                     │
             ┌─────────────────┐
             │ Windows 11 VM   │
             │ Sysmon          │
             │ Wazuh Agent     │
             └─────────────────┘
```

## Attack Scenarios
- Brute Force Login Attack
- Suspicious PowerShell Execution
- Privilege Escalation
- Data Exfiltration Simulation
- Malware Simulation (EICAR)
- Network Scanning (Reconnaissance)

## Key Features
- Real-time log monitoring and analysis
- Detection rule creation
- Incident response workflows
- Structured documentation (runbooks and reports)

## Skills Demonstrated
- SIEM Engineering
- Security Monitoring
- Log Analysis
- Alert Triage
- Incident Response
- Threat Hunting
- Detection Engineering
- Windows Security
- Linux Administration
- Network Troubleshooting
- Endpoint Monitoring
- IOC Analysis
- MITRE ATT&CK Mapping

# Future Work

- Brute Force Detection
- PowerShell Attack Detection
- Mimikatz Detection
- RDP Attack Detection
- Malware Detection
- IOC Hunting
- Custom Detection Rules
- Incident Response Playbooks

## Project Structure
See folders for setup, attack simulations, detection rules, and incident reports.

## Disclaimer
This project is intended for educational purposes only and should be conducted in an isolated lab environment.
