# Project 01 – Virtualization Foundation

## Status

✅ Completed

---

# Project Overview

This project established the virtualization foundation for the Home Lab environment.

The objective was to install a professional hypervisor, deploy a Linux virtual machine, verify system functionality, create a baseline snapshot, and prepare the environment for future enterprise infrastructure projects.

This project serves as the foundation for future Windows Server, Active Directory, Kali Linux, pfSense, and SIEM deployments.

---

# Objectives

- Install VMware Workstation Pro
- Create a Ubuntu virtual machine
- Install Ubuntu 24.04.4 LTS
- Configure a Linux administrator account
- Verify networking
- Verify Internet connectivity
- Update Ubuntu
- Create a recovery snapshot

---

# Environment

## Host System

- Windows 11 Home
- Intel Pentium Gold 7505
- 8 GB RAM

## Hypervisor

- VMware Workstation Pro 26H1

## Guest Operating System

- Ubuntu 24.04.4 LTS

---

# Virtual Machine Configuration

| Setting | Value |
|----------|-------|
| Memory | 2048 MB |
| Processors | 2 vCPUs |
| Disk | 30 GB |
| Disk Type | Single File |
| Network | NAT |
| Snapshot | Fresh Ubuntu Install |

---

# Installation Process

Completed the following:

- Installed VMware Workstation Pro
- Created Ubuntu virtual machine
- Mounted Ubuntu installation ISO
- Installed Ubuntu Desktop
- Configured administrator account
- Configured hostname
- Configured timezone
- Completed first boot
- Installed system updates
- Rebooted successfully
- Created initial snapshot

---

# Verification Commands

```bash
whoami
hostname
ip a
ping -c 4 ubuntu.com
```

---

# Verification Results

## User Verification

Verified administrator account.

## Hostname Verification

Hostname configured successfully.

```
ubuntu-lab
```

## Network Verification

Verified VMware NAT networking.

Network interface received an IPv4 address.

## Internet Verification

Successfully reached:

```
ubuntu.com
```

No packet loss observed.

---

# System Updates

Executed:

```bash
sudo apt update
sudo apt upgrade -y
```

All available updates installed successfully.

---

# Snapshot

Snapshot Name

```
Fresh Ubuntu Install
```

Purpose

- Clean baseline
- Recovery point
- Safe rollback before future projects

---

# Troubleshooting

## VirtualBox Compatibility Issues

Initially attempted virtualization using Oracle VirtualBox.

Observed:

- Black screen during boot
- Ubuntu boot failures
- Hypervisor conflicts
- Graphics compatibility issues

After investigation, VMware Workstation Pro was selected.

VMware provided stable virtualization and completed Ubuntu installation successfully.

---

# Lessons Learned

- VMware Workstation Pro provides reliable virtualization for Windows 11 Home.
- Always verify networking after operating system installation.
- System updates should be completed before additional configuration.
- Creating an initial snapshot protects the clean installation.
- Troubleshooting the virtualization platform before continuing saved significant time.

---

# Skills Demonstrated

- Virtualization
- VMware Workstation Pro
- Ubuntu Installation
- Linux Administration
- Virtual Networking
- System Updates
- Snapshot Management
- Troubleshooting
- Technical Documentation

---

# Next Project

Project 02 – Windows Server

Objectives

- Install Windows Server
- Configure server roles
- Prepare for Active Directory deployment