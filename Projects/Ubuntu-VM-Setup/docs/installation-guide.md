# Ubuntu Virtual Machine Installation Guide

This document outlines the process used to create my first Linux virtual machine using Oracle VirtualBox and Xubuntu.

---

# Objective

Build a Linux virtual machine for:

- Learning Linux fundamentals
- Practicing cybersecurity concepts
- Creating a home lab environment
- Developing troubleshooting and documentation skills

---

# Requirements

## Software

- Oracle VirtualBox
- Xubuntu 26.04 ISO
- Windows 11 Host Machine

---

# Installation Steps

## Step 1 – Download Oracle VirtualBox

Downloaded and installed Oracle VirtualBox on the Windows host machine.

---

## Step 2 – Download Xubuntu ISO

Downloaded the Xubuntu 26.04 installation image.

---

## Step 3 – Create a New Virtual Machine

Created a new virtual machine named:

```text
Cyber-Lab-Ubuntu
```

Selected:

```text
Linux
Ubuntu (64-bit)
```

---

## Step 4 – Configure Hardware

Allocated the following resources:

- 2048 MB RAM
- 1 CPU Core
- 25 GB Virtual Hard Disk

---

## Step 5 – Attach Installation Media

Mounted the Xubuntu ISO file to the virtual optical drive.

---

## Step 6 – Start the Virtual Machine

Booted the virtual machine for the first time.

---

## Step 7 – Installation Issue Encountered

The installer appeared to freeze during setup.

Symptoms included:

- Installer not progressing
- Loading spinner becoming unresponsive
- Desktop failing to load correctly

---

## Step 8 – Troubleshooting

Attempted several fixes:

- Restarted the virtual machine
- Reviewed VirtualBox settings
- Adjusted display settings
- Increased video memory

---

## Step 9 – Resolution

Selected:

```text
Ubuntu (Safe Graphics)
```

The operating system then booted successfully and the installation completed normally.

---

## Step 10 – Initial System Configuration

Completed the following tasks:

- Created a Linux user account
- Configured system settings
- Verified successful boot into the desktop environment
- Tested system functionality

---

# Installation Result

Successfully installed:

```text
Xubuntu 26.04
```

on a VirtualBox virtual machine.

The system is now ready for:

- Linux command-line practice
- Networking exercises
- Cybersecurity labs
- Future project development

---

# Lessons Learned

- Virtual machine display settings can impact operating system installation.
- Safe Graphics Mode can resolve compatibility issues.
- Troubleshooting often requires testing multiple solutions.
- Documenting the process makes future installations significantly easier.

---

# Future Improvements

- Increase system resources if needed.
- Create snapshots before major changes.
- Install additional cybersecurity tools.
- Build additional Linux virtual machines for lab environments.