# Project 01 – Virtualization Foundation Architecture

## Overview

This project establishes the foundational virtualization environment for the Home Lab. VMware Workstation Pro serves as the hypervisor, hosting an Ubuntu 24.04.4 LTS virtual machine that acts as the initial lab system. This baseline environment will support future infrastructure projects, including Windows Server, Active Directory, pfSense, SIEM, and other enterprise technologies.

---

# Architecture Objectives

- Build a reliable virtualization platform
- Deploy a stable Linux virtual machine
- Verify network connectivity
- Establish a clean baseline for future labs
- Create a recoverable snapshot before additional projects

---

# Host System

| Component | Specification |
|----------|---------------|
| Operating System | Windows 11 Home |
| Processor | Intel Pentium Gold 7505 |
| Memory | 8 GB RAM |
| Hypervisor | VMware Workstation Pro 26H1 |

---

# Virtual Machine

| Setting | Configuration |
|---------|---------------|
| Guest Operating System | Ubuntu 24.04.4 LTS |
| Memory | 2 GB |
| CPUs | 2 vCPUs |
| Storage | 30 GB Virtual Disk |
| Network Adapter | NAT |
| Firmware | UEFI (VMware Default) |

---

# Network Architecture

```
                    Internet
                        │
                        │
              Home Router / ISP
                        │
                        │
                 Windows 11 Host
                        │
        VMware Workstation Pro (NAT)
                        │
                        │
               Ubuntu 24.04.4 LTS VM
```

### Network Configuration

- Network Mode: NAT
- Internet Access: Verified
- Host-to-Guest Communication: Enabled through VMware NAT
- IP Address: Assigned dynamically by VMware's virtual network

---

# Software Stack

## Host

- Windows 11 Home
- VMware Workstation Pro 26H1

## Guest

- Ubuntu 24.04.4 LTS
- OpenSSH (future project)
- Development and administrative tools (future projects)

---

# Design Decisions

## VMware Workstation Pro

Selected because it provided reliable virtualization on the host system after VirtualBox experienced compatibility issues.

### Advantages

- Stable Ubuntu support
- Reliable networking
- Snapshot management
- Strong hardware compatibility
- Enterprise-standard virtualization platform

---

## Ubuntu 24.04.4 LTS

Chosen because it is a Long-Term Support (LTS) release, making it suitable for enterprise environments and long-term lab use.

### Advantages

- Five years of support
- Large community
- Widely used in production
- Excellent documentation

---

## NAT Networking

NAT was selected for the initial project because it provides:

- Internet connectivity
- Simple configuration
- Isolation from the physical network
- Safe environment for learning

Future projects may introduce additional virtual network configurations as needed.

---

# Baseline Validation

The following checks were successfully completed:

- VMware installation
- Ubuntu installation
- User authentication
- Hostname verification
- Network connectivity
- Internet connectivity
- System updates
- Initial snapshot creation

---

# Recovery Strategy

A VMware snapshot named **Fresh Ubuntu Install** was created after:

- Operating system installation
- System updates
- Connectivity verification

This snapshot serves as the project's baseline recovery point before future configuration changes.

---

# Future Expansion

This virtualization platform will support the following planned projects:

- Project 02 – Windows Server
- Project 03 – Active Directory
- Project 04 – osTicket
- Project 05 – pfSense
- Project 06 – SIEM

Additional virtual machines and network configurations will be added as the Home Lab environment grows.

---

# Architecture Summary

This project successfully established a stable virtualization environment capable of supporting future enterprise infrastructure projects. VMware Workstation Pro and Ubuntu 24.04.4 LTS provide a reliable foundation for expanding the Home Lab into a multi-system environment focused on systems administration, networking, cybersecurity, and IT operations.