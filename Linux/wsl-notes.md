# WSL (Windows Subsystem for Linux) Notes

## What is WSL?

WSL (Windows Subsystem for Linux) allows Linux distributions to run directly inside Windows without requiring a full virtual machine.

## Benefits

- Lightweight
- Faster than a virtual machine
- Great for command-line practice
- Useful for scripting and cybersecurity work
- Easy access to Linux tools on a Windows machine

---

# Installation Steps

1. Open PowerShell as Administrator.

2. Check WSL status:

```powershell
wsl --status
```

3. Install Ubuntu:

```powershell
wsl --install
```

4. Restart the computer if prompted.

5. Launch Ubuntu.

6. Create a Linux username and password.

---

# Installation Behavior

The Ubuntu installation appeared frozen at 49.1%.

I pressed `Ctrl + C`, and the installation immediately completed successfully.

This suggests that the installation itself had likely finished and only the progress display was stalled.

## Lesson Learned

Terminal output may not always accurately reflect the state of the underlying process.

---

# Concepts Learned

## WSL

Runs Linux directly inside Windows.

## WSL2

Uses lightweight virtualization and a real Linux kernel.

## Unix User Account

Linux requires its own user account and password.

## Troubleshooting

Always investigate before assuming something has failed.

---

# First WSL Login

Successfully installed Ubuntu through WSL.

Created Linux user:

- Username: jamaur1an

Opted out of Ubuntu telemetry collection.

Reached the first Linux shell:

```text
jamaur1an@DESKTOP-RR8P5KS:~$
```

This marked the beginning of Linux command-line practice directly on Windows without using a virtual machine.

---

# Launching Ubuntu After Installation

Accidentally closed the PowerShell window after installation.

Reopened Ubuntu from the Windows Start Menu.

Ubuntu launched successfully and presented the Linux shell prompt.

## Lesson Learned

Closing the terminal does not remove or break a WSL installation. The Linux environment persists on the system.

---

# First Successful WSL Login

Successfully launched Ubuntu through Windows Subsystem for Linux.

Terminal prompt:

```text
jamaur1an@DESKTOP-RR8P5KS:~$
```

This confirms:

- Ubuntu installation completed successfully.
- Linux user account was created.
- WSL environment is operational.

## Lesson Learned

The Linux shell prompt indicates that the operating system is ready for command-line interaction.

---

# WSL Installation Summary

**Date:** July 5, 2025

## Objective

Install Ubuntu through Windows Subsystem for Linux (WSL) to create a lightweight Linux environment for cybersecurity practice.

## Steps Performed

### Verified WSL Status

```powershell
wsl --status
```

Received error:

```text
WSL optional component not enabled.
```

### Attempted to Enable WSL Feature

```powershell
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
```

Received error:

```text
Feature name unknown.
```

### Enumerated Windows Features

```powershell
DISM /Online /Get-Features /Format:Table | findstr /i "linux"
DISM /Online /Get-Features /Format:Table | findstr /i "virtual"
```

### Restarted System

### Installed Ubuntu

```powershell
wsl --install
```

Created Linux user:

- Username: jamaur1an

Successfully reached Linux shell:

```text
jamaur1an@DESKTOP-RR8P5KS:~$
```

---

# Lessons Learned

- WSL can be used instead of a full virtual machine for Linux practice.
- Linux environments can be installed directly inside Windows.
- Terminal output can sometimes appear frozen while installation continues.
- Documentation and screenshots make troubleshooting easier.

---

# Cybersecurity Relevance

- Many cybersecurity tools run on Linux.
- WSL provides a lightweight Linux environment inside Windows.
- Useful for Bash scripting, Git, Python, and penetration testing tools.
- Allows Linux practice without dedicating an entire virtual machine.

---

# Next Steps

- Learn Linux commands and file navigation.
- Practice package management.
- Learn Bash scripting.
- Use WSL for Git and Python development.
- Begin using Linux tools for cybersecurity labs.