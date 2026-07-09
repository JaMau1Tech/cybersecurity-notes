# Windows Investigations

## Overview

This directory contains hands-on Windows investigations designed to reinforce Windows administration, system troubleshooting, and cybersecurity concepts through practical exercises.

Each investigation focuses on a specific topic using native Windows tools and follows a structured workflow consisting of planning, evidence collection, documentation, and analysis.

These investigations complement my TryHackMe learning by providing additional real-world practice and strengthening my command-line and investigative skills.

---

## Investigation Workflow

Each investigation follows the same documentation process:

1. Define the investigation objective.
2. Perform the hands-on investigation.
3. Collect supporting evidence (screenshots).
4. Document findings and lessons learned.
5. Organize evidence and documentation.
6. Commit the completed investigation to GitHub.

---

## Investigations

| Investigation | Focus | Status |
|---------------|-------|:------:|
| Investigation 01 – System Recon | Enumerating user, system, network, directory, and storage information using native Windows commands. | ✅ |
| Investigation 02 – Process Analysis | Investigating running processes, Windows services, and process filtering using the `tasklist` utility. | ✅ |
| Investigation 03 – Network Connections | Investigating active network connections, listening ports, and associated processes. | ⬜ |
| Investigation 04 – User & Account Enumeration | Enumerating local users, groups, and account information. | ⬜ |
| Investigation 05 – Scheduled Tasks | Investigating scheduled tasks and automated execution. | ⬜ |
| Investigation 06 – Event Logs | Exploring Windows Event Viewer and log analysis. | ⬜ |

---

## Skills Practiced

- Windows Command Prompt
- System Enumeration
- Process Enumeration
- Service Enumeration
- Network Enumeration
- File System Navigation
- Disk Enumeration
- Windows Administration
- Technical Documentation
- Incident Investigation

---

## Repository Structure

```text
Windows/
├── README.md
├── Investigation-01-System-Recon/
│   ├── README.md
│   ├── investigation-notes.md
│   └── screenshots/
│       └── README.md
│
├── Investigation-02-Process-Analysis/
│   ├── README.md
│   ├── investigation-notes.md
│   └── screenshots/
│       └── README.md
│
├── Investigation-03-Network-Connections/
├── Investigation-04-User-Account-Enumeration/
├── Investigation-05-Scheduled-Tasks/
└── Investigation-06-Event-Logs/
```

---

## Purpose

The goal of these investigations is to develop practical Windows investigation skills using built-in operating system tools while creating a professional portfolio that demonstrates hands-on experience with Windows system administration and basic incident response techniques.