# Linux CLI Basics

## Status

✅ Completed

---

## Overview

This room introduced the Linux Command-Line Interface (CLI) and the essential commands used to navigate the filesystem, locate files, and gather system information. Through hands-on exercises, I learned how to move through directories, inspect files, retrieve operating system details, and complete basic administrative tasks using the terminal.

---

## Learning Objectives

- Understand the Linux terminal and Command-Line Interface (CLI)
- Navigate the Linux filesystem
- Locate files and directories
- Read file contents
- Gather system information
- Identify operating system details
- Build confidence using the Linux terminal

---

## Key Concepts Learned

- Linux Terminal
- Command-Line Interface (CLI)
- Shell
- Filesystem
- Directory Navigation
- Home Directory (`~`)
- `pwd`
- `ls`
- `ls -l`
- `ls -al`
- `cd`
- `find`
- `cat`
- `whoami`
- `uname`
- `df -h`
- `/etc`
- `os-release`
- Kernel
- Linux Distribution

---

## Skills Practiced

- Opening and using the Linux terminal
- Navigating directories
- Listing files and folders
- Viewing hidden files
- Finding files using the `find` command
- Reading text files
- Gathering system information
- Checking disk usage
- Identifying Linux distribution information
- Technical documentation

---

## Lab / Hands-On

### Task 2 – Terminal Navigation

1. Open the Linux terminal.
2. Display the current working directory:

   ```bash
   pwd
   ```

3. List the contents of the current directory:

   ```bash
   ls
   ls -l
   ls -al
   ```

4. Navigate into the **Documents** directory:

   ```bash
   cd Documents
   ```

5. Return to the previous directory:

   ```bash
   cd ..
   ```

6. Locate the mission file:

   ```bash
   find ~ -name mission_brief.txt
   ```

7. Navigate to the folder containing the file:

   ```bash
   cd <path>
   ```

8. Verify the file exists:

   ```bash
   ls
   ```

9. Read the file contents and record the flag:

   ```bash
   cat mission_brief.txt
   ```

---

### Task 3 – Gathering System Information

1. Display the current logged-in user:

   ```bash
   whoami
   ```

2. View kernel and system information:

   ```bash
   uname -a
   ```

3. Check disk usage:

   ```bash
   df -h
   ```

4. Navigate to the system configuration directory:

   ```bash
   cd /etc
   ```

5. List the directory contents:

   ```bash
   ls
   ```

6. Display Linux distribution information:

   ```bash
   cat os-release
   ```

7. Locate the challenge report:

   ```bash
   find ~ -name day1_report.txt
   ```

8. Navigate to the file's location.

9. Read the report to complete the room:

   ```bash
   cat day1_report.txt
   ```

---

## Lab Evidence

### Introduction

- No screenshots required

### Terminal Navigation

- linux-task2-pwd-command-output
- linux-task2-ls-long-listing
- linux-task2-hidden-files-output
- linux-task2-directory-navigation
- linux-task2-find-mission-brief
- linux-task2-mission-brief-flag

### System Information

- linux-task3-whoami-output
- linux-task3-uname-output
- linux-task3-disk-space
- linux-task3-etc-directory
- linux-task3-os-release
- linux-task3-find-day1-report
- linux-task3-day1-report

---

## Personal Reflection

This room helped me become much more comfortable using the Linux terminal. Learning how to navigate the filesystem, locate files, retrieve system information, and use common commands gave me practical skills that are used daily by system administrators and cybersecurity professionals. I now feel more confident working in Linux environments and understand why command-line proficiency is an essential cybersecurity skill.