# Mission 4 Implementation Notes

## Architectural Significance

Mission 4 represents the transition from building infrastructure to operating it. Previous Missions focused on deploying, securing, and validating the lab environment. Beginning with the next Mission, the emphasis shifts toward automation, repeatable workflows, and security operations using the foundation established throughout the first four Missions.

---

## Design Decisions

### Why Install Python?

Python was installed on the management workstation to support future automation projects involving scripting, API integration, data analysis, and security workflow development. While Python is capable of many tasks, it was intentionally introduced only after the lab foundation had been fully validated.

---

### Why Install PowerShell 7?

PowerShell 7 provides a modern, cross-platform automation framework capable of administering both Windows and Linux systems. Future Missions will leverage PowerShell to automate repetitive administrative tasks while interacting with multiple systems throughout the lab.

---

### Why Verify Remote Desktop?

Remote Desktop was validated to ensure the management workstation could reliably administer Windows systems within the lab. Verifying connectivity before automation eliminates unnecessary troubleshooting later when remote administration becomes part of larger workflows.

---

### Why Verify SSH?

SSH provides secure command-line administration for Linux systems. Confirming SSH connectivity establishes a dependable management channel for future automation, scripting, and remote system administration.

---

### Why Keep Git and GitHub Outside the Lab?

Development tools, including Git and GitHub, were intentionally maintained on the primary workstation rather than inside the virtual lab. This design keeps personal accounts separate from the lab environment while still allowing scripts, documentation, and configuration files to be transferred into the lab when needed. The decision reflects the principle of keeping systems purpose-built while minimizing unnecessary exposure of personal credentials.

---

## Validation Performed

- Confirmed successful installation of Python 3
- Confirmed successful installation of PowerShell 7
- Verified Remote Desktop connectivity
- Verified SSH connectivity to the Ubuntu Server
- Confirmed the management workstation was fully operational
- Validated readiness for future automation projects

---

## Lessons Learned

- A well-tested foundation simplifies future automation
- Remote administration should be validated before relying on automated workflows
- Development tools should be installed with a clear purpose rather than by default
- Separating development resources from the lab environment reduces unnecessary risk while preserving flexibility
- Automation is most effective when built upon a stable, validated infrastructure