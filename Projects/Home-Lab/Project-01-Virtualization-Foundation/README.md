# Project 01 – Virtualization Foundation

## Overview

This project establishes the virtualization foundation for my Home Lab using VMware Workstation Pro and Ubuntu 24.04.4 LTS. The goal was to create a stable, repeatable environment that will support future infrastructure projects, including Windows Server, Active Directory, pfSense, osTicket, and SIEM deployments.

This project serves as the baseline for the entire Home Lab environment.

---

## Objectives

- Install VMware Workstation Pro
- Deploy Ubuntu 24.04.4 LTS
- Configure a virtual machine
- Verify network connectivity
- Update the operating system
- Create a baseline recovery snapshot
- Prepare the environment for future projects

---

## Technologies Used

### Host

- Windows 11 Home
- VMware Workstation Pro 26H1

### Guest

- Ubuntu 24.04.4 LTS

---

## Virtual Machine Configuration

| Setting | Value |
|---------|-------|
| Memory | 2 GB |
| CPUs | 2 vCPUs |
| Storage | 30 GB |
| Network | NAT |

---

## Project Walkthrough

### 1. Installed VMware Workstation Pro

Configured VMware Workstation Pro as the primary virtualization platform after evaluating virtualization options.

---

### 2. Created Ubuntu Virtual Machine

Configured a virtual machine with appropriate hardware resources and attached the Ubuntu installation media.

---

### 3. Installed Ubuntu

Completed the Ubuntu 24.04.4 LTS installation, including user account creation, hostname configuration, and timezone selection.

---

### 4. Verified System Functionality

Confirmed:

- User authentication
- Hostname
- Network connectivity
- Internet access

---

### 5. Updated the Operating System

Executed:

```bash
sudo apt update
sudo apt upgrade -y
```

Installed all available updates before proceeding with future projects.

---

### 6. Created Baseline Snapshot

Created the VMware snapshot:

**Fresh Ubuntu Install**

This snapshot serves as a recovery point before additional software or services are installed.

---

## Screenshots

| Screenshot | Description |
|------------|-------------|
| `project-01-ubuntu-installer-welcome` | Ubuntu installation started |
| `project-01-virtualization-foundation-first-successful-boot` | First successful boot |
| `project-01-virtualization-foundation-first-desktop` | Ubuntu desktop after installation |
| `project-01-virtualization-foundation-desktop-ready` | Desktop environment ready for use |
| `project-01-virtualization-foundation-terminal-verification` | Verification commands executed successfully |
| `project-01-virtualization-foundation-system-updated` | System updates completed |
| `project-01-virtualization-foundation-post-update-desktop` | Desktop after reboot following updates |
| `project-01-virtualization-foundation-first-snapshot` | VMware baseline snapshot created |

---

## Skills Demonstrated

- Virtualization
- VMware Workstation Pro
- Ubuntu Linux
- Linux Administration
- Virtual Networking
- Operating System Deployment
- System Updates
- Snapshot Management
- Troubleshooting
- Technical Documentation

---

## Key Outcomes

- Successfully deployed Ubuntu in VMware Workstation Pro
- Verified network and Internet connectivity
- Updated the operating system
- Established a clean baseline snapshot
- Prepared the environment for future enterprise infrastructure projects

---

## Lessons Learned

- Selecting the appropriate virtualization platform is critical for system stability.
- Verifying connectivity immediately after installation helps identify issues early.
- Creating a baseline snapshot provides a reliable rollback point.
- Completing system updates before additional configuration reduces future maintenance issues.

---

## Related Documentation

- `project-notes.md` – Detailed build notes, commands, verification, and troubleshooting
- `architecture.md` – Virtual machine architecture and design decisions

---

## Next Project

**Project 02 – Windows Server**

The next phase of the Home Lab will introduce Windows Server, laying the foundation for Active Directory and other enterprise services.