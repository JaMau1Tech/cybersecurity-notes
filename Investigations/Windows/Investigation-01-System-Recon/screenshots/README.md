# Investigation 01 Screenshots

## Overview

This directory contains the evidence collected during the Windows System Recon investigation. Each screenshot documents the output of a Windows command used to gather information about the local system.

---

## Screenshot Evidence

| Screenshot | Description |
|------------|-------------|
| windows-user-information.png | Output of the `whoami` and `hostname` commands showing the current logged-in user and computer name. |
| windows-system-information.png | Output of the `systeminfo` command displaying operating system, hardware, BIOS, memory, and system configuration details. |
| windows-network-information.png | Output of the `ipconfig` command showing network adapters, IP addresses, subnet masks, gateway, and DNS configuration. |
| windows-directory-listing.png | Output of the `dir` command displaying the contents of the current user directory. |
| windows-disk-volumes.png | Output of the `diskpart` utility using the `list volume` command to enumerate available storage volumes and partitions. |

---

## Investigation Purpose

The screenshots in this folder provide supporting evidence for **Investigation 01 – Windows System Recon**, demonstrating how built-in Windows command-line tools can be used to enumerate system information during a basic host investigation.