# Hupfen Security Lab

*A hands-on cybersecurity portfolio documenting practical security engineering, technical experimentation, and continuous professional development across multiple cybersecurity domains.*

---

## Overview

This repository documents a segmented, enterprise-style cybersecurity lab built to support practical work across security operations, vulnerability management, telemetry engineering, detection engineering, and controlled security testing.

The lab is designed around validation rather than simple tool installation. Projects demonstrate the complete workflow from controlled activity and telemetry generation through centralized collection, SIEM analysis, alerting, investigation, documentation, and version control.

Many projects are accompanied by articles published on the Hupfen Dynamics blog that explain the design decisions, challenges, validation methods, and lessons learned behind each build.

---

## Areas of Focus

This repository demonstrates experience in:

- Virtualization & Lab Design
- Windows & Linux Administration
- Virtual Networking & Segmentation
- Security Hardening
- Security Operations
- Vulnerability Management
- Security Telemetry Engineering
- Detection Engineering
- Governance, Risk & Compliance
- Incident Investigation
- Technical Documentation
- Git & GitHub

---

## Current Lab Environment

| Component | Configuration |
|-----------|---------------|
| Host System | HP Envy Laptop |
| Processor | Intel Core i7 (11th Generation) |
| Memory | 16 GB RAM |
| Host OS | Windows 11 Home |
| Hypervisor | VMware Workstation Pro |
| Firewall / Router | pfSense |
| SIEM | Splunk Enterprise |
| Vulnerability Scanner | Nessus Essentials |
| Network IDS | Suricata |
| Windows Telemetry | Windows Security Logs & Sysmon |
| Linux Telemetry | auditd & system logs |
| Security Testing | Kali Linux & Nmap |

The environment uses separate USERS, MGMT, and CDE network segments routed through pfSense so that segmentation, telemetry collection, vulnerability scanning, detection logic, and analyst workflows can be tested in a controlled environment.

---

## Portfolio Highlights

### Completed Missions

- [Mission 1 - Installing a Hypervisor](labs/mission-01-hypervisor-setup)
- [Mission 2.0 - Building a Weak Windows VM](labs/mission-02-0-windows-vm)
- Mission 2.1 - Hardening the Weak Windows VM
- [Mission 2.5 - Building a Strong Windows VM](labs/mission-02-5-strong-windows-vm)
- Mission 2.6 - Strengthening the Windows VM
- [Mission 3 - Building a Linux VM Server](labs/mission-03-linux-server)
- [Mission 4 - Complete the Foundation: From Building to Automating](labs/mission-04-from-building-to-automating)

Additional mission material and walkthroughs are available through the Hupfen Dynamics blog.

### Security Projects - Completed

1. [Building and Validating a PCI DSS-Inspired Security Operations Lab](projects/pci-dss-compliance)  
   Segmentation, centralized logging, intrusion detection, alerting, investigation, and security-control validation.

2. [Vulnerability Management Program](projects/vulnerability-management)  
   Asset discovery, vulnerability scanning, risk-based prioritization, remediation, validation, and reporting.

3. [Modernizing the Security Telemetry Pipeline](projects/modernizing-security-telemetry-pipeline)  
   Structured Suricata EVE JSON telemetry, improved network visibility, and validated Splunk ingestion.

4. [Detection Engineering Program](projects/detection-engineering)  
   Four validated detections covering failed Windows logins, PowerShell execution, network reconnaissance, and Windows account creation.

Together, these projects form a connected progression from infrastructure and visibility to vulnerability management, telemetry improvement, and validated detection engineering.

---

## Skills Demonstrated

Throughout these projects, I have applied and documented experience with:

- VMware Workstation Pro
- pfSense
- Splunk Enterprise
- Nessus Essentials
- Suricata IDS
- Sysmon
- Windows Security Event Logs
- Linux auditd
- Kali Linux
- Nmap
- Splunk SPL
- Security Monitoring & Alerting
- Vulnerability Assessment & Remediation Validation
- Detection Development & Testing
- Network Segmentation
- Technical Documentation
- Troubleshooting
- Git & GitHub

---

## Supporting Blog

Many of these projects include expanded walkthroughs, lessons learned, and technical discussions on the Hupfen Dynamics blog.

[Hupfen Dynamics Blog](https://hupfendynamics.com/blog)

---

## Disclaimer

All projects are performed in isolated lab environments for educational, research, and portfolio purposes. The PCI DSS-related work is PCI DSS-inspired and control-aligned; it is not a formal PCI DSS certification or compliance assessment. No testing is conducted against production systems or infrastructure without authorization.
