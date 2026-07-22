# Architecture – Project 02: Windows Server Foundation

## Overview

This document describes the architecture, configuration, and purpose of the Windows Server virtual machine built during Project 02.

The server serves as the enterprise infrastructure foundation for the Home Lab and will later be promoted to an Active Directory Domain Controller.

---

# Architecture Summary

## Hypervisor

VMware Workstation Pro

## Host Operating System

Windows 11

## Guest Operating System

Windows Server 2022 Standard Evaluation (Desktop Experience)

---

# Virtual Machine Specifications

| Component | Configuration |
|-----------|---------------|
| VM Name | Windows Server 2022 |
| Hostname | SRV-DC01 |
| Computer Description | Primary Domain Controller |
| Firmware | UEFI |
| Memory | 4 GB |
| CPU | 2 vCPUs |
| Disk Size | 60 GB |
| Disk Controller | SCSI |
| Network Adapter | NAT |
| VMware Tools | Installed |
| Snapshot | Windows Server Baseline |

---

# Network Configuration

## IPv4 Configuration

| Setting | Value |
|---------|-------|
| IP Address | 192.168.45.129 |
| Subnet Mask | 255.255.255.0 |
| Default Gateway | 192.168.45.2 |
| Network Type | NAT |

---

# Network Layout

```text
                Internet
                    │
                    │
         Windows Host Computer
                    │
         VMware Workstation Pro
                    │
          VMware NAT Network
                    │
          ┌──────────────────┐
          │                  │
          │    SRV-DC01      │
          │ Windows Server   │
          │ 192.168.45.129   │
          │                  │
          └──────────────────┘
```

---

# Server Purpose

Current Responsibilities

- Windows Server installation
- Enterprise server baseline
- Virtual infrastructure foundation

Future Responsibilities

- Active Directory Domain Services
- DNS Server
- Authentication
- Group Policy
- Domain Controller
- User Management
- Computer Management

---

# Software Installed

## Operating System

- Windows Server 2022 Standard Evaluation

## Virtualization Components

- VMware Tools

## Windows Components

- Server Manager
- Windows PowerShell
- Windows Update

---

# Security Baseline

Completed

- Windows fully updated
- VMware Tools installed
- Enterprise hostname configured
- Static IPv4 address assigned
- Baseline snapshot created

Future Configuration

- Active Directory
- DNS
- DHCP (optional)
- Group Policy
- Organizational Units
- Security Groups
- User Accounts

---

# Verification Performed

## Operating System

- Successful installation
- Successful login
- GUI verified

## Network

- Static IP verified
- Gateway verified
- Internet connectivity verified
- DNS resolution verified

## Virtual Machine

- VMware Tools verified
- Snapshot created
- Stable boot confirmed

---

# Recovery

## VMware Snapshot

Snapshot Name

Windows Server Baseline

Purpose

Provides a rollback point before deploying enterprise infrastructure services.

---

# Project Dependencies

## Previous Project

Project 01

Ubuntu Foundation

Purpose

Linux administration practice and virtualization fundamentals.

---

## Next Project

Project 03

Active Directory

Objectives

- Install AD DS
- Install DNS
- Promote SRV-DC01
- Create Forest
- Create Domain
- Verify Authentication
- Join Windows 11 Client

---

# Overall Home Lab Architecture

```text
                          Home Lab

                    VMware Workstation
                           │
        ┌──────────────────┼──────────────────┐
        │                  │                  │
        │                  │                  │
   Ubuntu 24.04        Windows Server     Windows 11
      Project 01          Project 02       Project 04
                            │
                            │
                  Active Directory
                        Project 03
                            │
             ┌──────────────┴──────────────┐
             │                             │
        Domain Users                 Domain Computers

                 Future Infrastructure

        pfSense Firewall
        SIEM Platform
        Security Monitoring
```

---

# Architecture Summary

This Windows Server virtual machine serves as the core infrastructure server for the Home Lab.

All future Windows-based enterprise services—including Active Directory, DNS, authentication, Group Policy, and domain management—will be deployed from this system.

The baseline snapshot provides a stable recovery point before introducing additional server roles.