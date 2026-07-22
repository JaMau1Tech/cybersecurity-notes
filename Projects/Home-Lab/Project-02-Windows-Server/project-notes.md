# Project 02 – Windows Server Foundation

## Status

✅ Completed

---

# Overview

This project focused on building the Windows Server foundation for the Home Lab. A Windows Server 2022 virtual machine was deployed in VMware Workstation Pro, configured using enterprise best practices, updated, optimized with VMware Tools, assigned a static IP address, and prepared as the future Active Directory Domain Controller.

This project establishes the baseline server that will be used throughout the remaining Home Lab projects.

---

# Objectives

- Deploy Windows Server 2022
- Configure VMware virtual hardware
- Perform a manual operating system installation
- Configure enterprise server settings
- Install VMware Tools
- Apply Windows Updates
- Configure a static IP address
- Create a VMware recovery snapshot
- Prepare the server for Active Directory

---

# Environment

## Host System

- Windows 11
- VMware Workstation Pro

## Guest Operating System

- Windows Server 2022 Standard Evaluation
- Desktop Experience (GUI)

---

# Virtual Machine Configuration

| Component | Configuration |
|-----------|---------------|
| Hypervisor | VMware Workstation Pro |
| Firmware | UEFI |
| Memory | 4 GB |
| Processors | 2 vCPUs |
| Hard Disk | 60 GB |
| Disk Controller | SCSI |
| Network | NAT |
| VMware Tools | Installed |

---

# Installation Process

## VM Creation

A Windows Server 2022 virtual machine was created manually instead of using VMware Easy Install due to installation issues encountered during initial deployment.

### Configuration

- UEFI firmware
- SCSI virtual disk
- 60 GB virtual disk
- 4 GB RAM
- 2 vCPUs
- NAT networking

---

## Operating System Installation

Windows Server 2022 Standard Evaluation (Desktop Experience) was installed successfully using the ISO image.

The Desktop Experience edition was selected to provide a graphical user interface suitable for learning Windows Server administration.

---

# Initial Server Configuration

## Server Name

Hostname:

SRV-DC01

Computer Description:

Primary Domain Controller

The server naming convention follows enterprise standards and prepares the system for future Active Directory deployment.

---

## Windows Updates

Performed:

- Windows Update
- Installed available updates
- Restarted server
- Verified successful installation

---

## VMware Tools

VMware Tools was installed successfully.

Benefits:

- Improved graphics performance
- Enhanced mouse integration
- Better display resizing
- Time synchronization
- Optimized virtual hardware drivers
- Graceful shutdown support

---

# Network Configuration

## Static IPv4 Configuration

| Setting | Value |
|---------|-------|
| IPv4 Address | 192.168.45.129 |
| Subnet Mask | 255.255.255.0 |
| Default Gateway | 192.168.45.2 |

Internet connectivity was verified after assigning the static IP address.

---

# Verification

The following commands were executed to validate the installation.

```powershell
hostname
```

Verified:

- Hostname changed successfully

---

```powershell
whoami
```

Verified:

- Administrator account

---

```powershell
ipconfig
```

Verified:

- Static IP configuration
- Gateway
- Subnet mask

---

```powershell
ping google.com
```

Verified:

- Internet connectivity
- DNS resolution
- Network functionality

---

# VMware Snapshot

Snapshot Name:

Windows Server Baseline

Purpose:

Provides a recovery point after completing the initial server configuration and before installing Active Directory.

---

# Challenges Encountered

## VMware Easy Install Failure

Issue:

VMware Easy Install generated Windows licensing errors during deployment.

Resolution:

The operating system was installed manually using the Windows Server ISO.

---

## VMware Tools Restart

Issue:

The server remained on the "Getting Windows ready" screen for an extended period after installing VMware Tools.

Resolution:

After confirming VMware activity had stopped, the virtual machine was reset. Windows booted successfully and VMware Tools functioned correctly.

---

## Lessons Learned

- Manual Windows Server installation provides greater reliability than VMware Easy Install.
- VMware Tools should be installed immediately after operating system installation.
- Static IP addresses are required before deploying Active Directory.
- Enterprise hostnames improve administration and documentation.
- Creating recovery snapshots before major changes greatly simplifies troubleshooting.

---

# Skills Developed

## Virtualization

- VMware Workstation Pro
- Virtual machine creation
- Snapshot management

## Windows Server

- Windows Server installation
- Server Manager
- Windows administration

## Networking

- IPv4 configuration
- Static addressing
- Connectivity testing

## System Administration

- Windows Update
- VMware Tools
- PowerShell verification

---

# Project Outcome

Successfully deployed and configured a Windows Server 2022 virtual machine using enterprise best practices.

The server now serves as the foundation for future Home Lab projects including:

- Active Directory Domain Services
- DNS
- DHCP
- Group Policy
- Windows 11 domain joining
- Enterprise user and computer management

---

# Next Project

Project 03 – Active Directory

Objectives:

- Install Active Directory Domain Services
- Install DNS Server
- Promote SRV-DC01 to a Domain Controller
- Create a new forest
- Create the lab domain
- Verify Active Directory functionality