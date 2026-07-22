# Project 02 – Windows Server Foundation

## Overview

Project 02 focuses on deploying and configuring a Windows Server 2022 virtual machine that serves as the core infrastructure server for the Home Lab.

The server was manually installed in VMware Workstation Pro, configured using enterprise best practices, updated, optimized with VMware Tools, assigned a static IP address, and prepared for future Active Directory deployment.

This project establishes the foundation for the Windows-based enterprise environment that will be expanded throughout the remaining Home Lab projects.

---

## Objectives

- Deploy Windows Server 2022
- Configure enterprise virtual hardware
- Install Windows Server manually
- Configure a static IP address
- Install VMware Tools
- Apply Windows Updates
- Configure enterprise hostname
- Create a VMware baseline snapshot
- Prepare for Active Directory

---

## Technologies Used

### Virtualization

- VMware Workstation Pro

### Operating System

- Windows Server 2022 Standard Evaluation
- Desktop Experience (GUI)

### Networking

- IPv4
- NAT Networking
- Static IP Configuration

### Administration

- Windows Server Manager
- Windows PowerShell
- Windows Update

---

## Virtual Machine Configuration

| Component | Configuration |
|-----------|---------------|
| Hypervisor | VMware Workstation Pro |
| Firmware | UEFI |
| Memory | 4 GB |
| CPU | 2 vCPUs |
| Disk | 60 GB |
| Disk Controller | SCSI |
| Network | NAT |
| VMware Tools | Installed |

---

## Server Configuration

| Setting | Value |
|---------|-------|
| Hostname | SRV-DC01 |
| Description | Primary Domain Controller |
| IPv4 Address | 192.168.45.129 |
| Subnet Mask | 255.255.255.0 |
| Default Gateway | 192.168.45.2 |

---

## Project Workflow

- Create virtual machine
- Install Windows Server
- Configure enterprise settings
- Install VMware Tools
- Apply Windows Updates
- Configure static networking
- Verify connectivity
- Create baseline snapshot

---

## Skills Developed

### Windows Server

- Windows Server installation
- Server Manager administration
- Windows Updates
- Enterprise configuration

### Virtualization

- VMware virtual machine deployment
- VMware Tools installation
- Snapshot management

### Networking

- IPv4 configuration
- Static addressing
- Network verification
- Internet connectivity testing

### PowerShell

- Hostname verification
- Network verification
- Connectivity testing

---

## Screenshots

| Screenshot | Description |
|------------|-------------|
| project-02-windows-server-vm-created | Virtual machine created |
| project-02-windows-server-installation | Windows installation |
| project-02-windows-server-first-login | First successful login |
| project-02-windows-server-server-manager | Server Manager dashboard |
| project-02-windows-server-terminal-verification | PowerShell verification |
| project-02-windows-server-renamed | Enterprise hostname configured |
| project-02-vmware-tools-installed | VMware Tools installation |
| project-02-windows-server-static-ip | Static IP configuration |
| project-02-windows-server-baseline-snapshot | VMware baseline snapshot |

---

## Challenges Encountered

### VMware Easy Install

VMware Easy Install failed during deployment due to Windows licensing issues.

**Resolution**

The virtual machine was recreated and Windows Server was installed manually using the installation ISO.

---

### VMware Tools Restart

The server remained on the **Getting Windows ready** screen after installing VMware Tools.

**Resolution**

After verifying that VMware activity had stopped, the virtual machine was safely reset and booted normally.

---

## Lessons Learned

- Manual Windows Server installation provides greater reliability than VMware Easy Install.
- Enterprise naming conventions improve server administration.
- Static IP addresses should be configured before Active Directory deployment.
- VMware Tools significantly improve virtual machine usability.
- Baseline snapshots simplify recovery and future experimentation.

---

## Project Outcome

Successfully deployed and configured a production-style Windows Server virtual machine.

Completed tasks include:

- Windows Server installation
- Enterprise hostname configuration
- Static IP configuration
- VMware Tools installation
- Windows Updates
- Network verification
- Baseline VMware snapshot

The server is now fully prepared for Active Directory deployment.

---

## Project Structure

```text
Project-02-Windows-Server/
├── README.md
├── architecture.md
├── project-notes.md
└── images/
    ├── project-02-windows-server-vm-created.png
    ├── project-02-windows-server-installation.png
    ├── project-02-windows-server-first-login.png
    ├── project-02-windows-server-server-manager.png
    ├── project-02-windows-server-terminal-verification.png
    ├── project-02-windows-server-renamed.png
    ├── project-02-vmware-tools-installed.png
    ├── project-02-windows-server-static-ip.png
    └── project-02-windows-server-baseline-snapshot.png
```

---

## Next Project

### Project 03 – Active Directory

Upcoming objectives:

- Install Active Directory Domain Services (AD DS)
- Install DNS Server
- Promote **SRV-DC01** to a Domain Controller
- Create a new Active Directory forest
- Configure the lab domain
- Create Organizational Units (OUs)
- Create users and groups
- Join a Windows 11 client to the domain

---

## Author

**J Wi**

Home Lab Series

Project 02 – Windows Server Foundation