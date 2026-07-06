# VirtualBox Configuration

This document records the configuration used to create my first Ubuntu virtual machine.

---

# Virtual Machine Information

## Virtual Machine Name

```text
Cyber-Lab-Ubuntu
```

## Operating System

```text
Ubuntu 25.04 (64-bit)
```

---

# Hardware Configuration

## Memory (RAM)

```text
2048 MB
```

Reason:
Allocated enough memory to run Ubuntu while still leaving resources available for the Windows host operating system.

---

## Processor

```text
1 CPU Core
```

Reason:
Sufficient for basic Linux learning, command-line practice, and introductory cybersecurity labs.

---

## Virtual Hard Disk

```text
25 GB
```

Reason:
Provides adequate space for Ubuntu, software updates, screenshots, notes, and future learning tools.

---

# Display Configuration

## Graphics Controller

```text
VBoxSVGA
```

## Video Memory

```text
128 MB
```

Reason:
Provides improved graphical performance and compatibility with Ubuntu Desktop.

---

# Network Configuration

## Adapter Type

```text
NAT
```

Reason:
Allows the virtual machine to access the internet through the host computer while keeping the virtual machine isolated from the local network.

---

# Issues Encountered

## Installation Freeze

The Ubuntu installer appeared to freeze during installation.

### Troubleshooting Performed

- Verified VirtualBox settings.
- Increased video memory.
- Restarted the virtual machine.
- Attempted installation again.

### Resolution

Booted Ubuntu using:

```text
Safe Graphics Mode
```

The installation then completed successfully.

---

# Lessons Learned

- Virtual machine display settings can affect operating system installation.
- Safe Graphics Mode can resolve compatibility issues during Ubuntu installation.
- Recording system configurations makes troubleshooting much easier in the future.
- Documentation is an important skill in both IT and cybersecurity.

---

# Future Improvements

- Increase RAM to 4096 MB if additional tools are installed.
- Experiment with Bridged Networking.
- Create additional Linux virtual machines for cybersecurity labs.
- Build a dedicated penetration testing lab.