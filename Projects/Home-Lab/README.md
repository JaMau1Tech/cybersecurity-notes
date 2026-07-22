# Home Lab

## Overview

This repository documents the development of a hands-on enterprise Home Lab built to strengthen practical IT and cybersecurity skills through real-world infrastructure projects.

The environment is hosted in VMware Workstation Pro and is designed to simulate a small enterprise network. Projects build upon one another, beginning with virtualization and operating system deployment before progressing into enterprise services such as Active Directory, DNS, Group Policy, networking, security monitoring, and system administration.

---

# Objectives

- Develop practical system administration skills
- Build enterprise Windows infrastructure
- Practice Linux administration
- Gain experience with virtualization
- Configure enterprise networking
- Deploy Active Directory services
- Implement identity and access management
- Prepare for cybersecurity and IT operations roles

---

# Lab Environment

## Host Platform

- Windows 11
- VMware Workstation Pro

## Virtual Machines

| Virtual Machine | Status | Purpose |
|-----------------|:------:|---------|
| Ubuntu 24.04 LTS | ✅ Complete | Linux administration and virtualization foundation |
| Windows Server 2022 | ✅ Complete | Enterprise infrastructure server |
| Windows 11 Client | ⏳ Planned | Domain-joined workstation |
| pfSense Firewall | ⏳ Planned | Network security and routing |
| Additional Security Systems | ⏳ Planned | Future security projects |

---

# Completed Projects

## ✅ Project 01 – Ubuntu Foundation

### Objectives

- Install Ubuntu Server
- Configure Linux
- Practice command-line administration
- Learn virtualization fundamentals

### Skills Developed

- VMware Workstation
- Ubuntu Server
- Linux CLI
- SSH
- Package management
- System administration

---

## ✅ Project 02 – Windows Server Foundation

### Objectives

- Deploy Windows Server 2022
- Configure enterprise virtual hardware
- Install Windows manually
- Configure enterprise hostname
- Install VMware Tools
- Apply Windows Updates
- Configure static networking
- Create baseline snapshot

### Skills Developed

- Windows Server administration
- VMware virtualization
- Static IPv4 configuration
- Windows Updates
- PowerShell verification
- Snapshot management
- Enterprise server deployment

---

# Project Roadmap

| Project | Status |
|---------|:------:|
| Project 01 – Ubuntu Foundation | ✅ Complete |
| Project 02 – Windows Server Foundation | ✅ Complete |
| Project 03 – Active Directory | ⏳ Next |
| Project 04 – Windows 11 Client | ⏳ Planned |
| Project 05 – Group Policy | ⏳ Planned |
| Project 06 – File Services | ⏳ Planned |
| Project 07 – Security Hardening | ⏳ Planned |
| Project 08 – Monitoring & Logging | ⏳ Planned |

---

# Current Lab Architecture

```text
                    VMware Workstation Pro
                            │
        ┌───────────────────┼───────────────────┐
        │                   │                   │
        │                   │                   │
 Ubuntu 24.04         Windows Server      Windows 11
  Project 01            SRV-DC01            Planned
                           │
                           │
                  Active Directory
                    (Next Project)
```

---

# Skills Gained

## Virtualization

- VMware Workstation Pro
- Virtual machine deployment
- Virtual hardware configuration
- Snapshot management

## Linux

- Ubuntu administration
- Linux command line
- Package management
- System configuration

## Windows

- Windows Server installation
- Server Manager
- Windows Updates
- PowerShell
- Enterprise configuration

## Networking

- IPv4 addressing
- Static IP configuration
- NAT networking
- Connectivity verification

---

# Repository Structure

```text
Home-Lab/
├── README.md
├── Project-01-Ubuntu-Foundation/
│   ├── README.md
│   ├── architecture.md
│   ├── project-notes.md
│   └── images/
├── Project-02-Windows-Server/
│   ├── README.md
│   ├── architecture.md
│   ├── project-notes.md
│   └── images/
├── Project-03-Active-Directory/
├── Project-04-Windows-11-Client/
├── Project-05-Group-Policy/
├── Project-06-File-Services/
├── Project-07-Security-Hardening/
└── Project-08-Monitoring-Logging/
```

---

# Progress

| Metric | Status |
|--------|--------|
| Projects Completed | **2 / 8** |
| Current Project | **Project 03 – Active Directory** |
| Infrastructure Status | **Windows Server Foundation Complete** |

---

# Next Project

## Project 03 – Active Directory

### Planned Objectives

- Install Active Directory Domain Services (AD DS)
- Install DNS Server
- Promote **SRV-DC01** to a Domain Controller
- Create a new Active Directory forest
- Configure the lab domain
- Create Organizational Units (OUs)
- Create security groups
- Create user accounts
- Verify authentication
- Prepare for Windows 11 domain join

---

# Author

**J Wi**

Enterprise Home Lab Portfolio