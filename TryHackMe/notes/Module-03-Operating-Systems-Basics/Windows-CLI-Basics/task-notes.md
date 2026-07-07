# Windows CLI Basics

## Status

✅ Completed

---

## Overview

This room introduced the Windows Command Prompt (CMD) and the essential commands used to navigate the Windows filesystem, locate files, read file contents, and gather system and network information. Through hands-on exercises, I practiced common administrative tasks that are frequently used by IT professionals and cybersecurity analysts.

---

## Learning Objectives

- Understand the Windows Command Prompt (CMD)
- Navigate the Windows filesystem
- Locate files using the command line
- Read file contents
- Gather system information
- Gather network information
- Build confidence using Windows CLI tools

---

## Key Concepts Learned

- Command Prompt (CMD)
- Command-Line Interface (CLI)
- Directory Navigation
- File Paths
- Hidden Files
- User Accounts
- Computer Hostname
- Windows System Information
- Network Configuration
- IPv4 Address
- Default Gateway
- `cd`
- `dir`
- `dir /a`
- `dir /s`
- `type`
- `whoami`
- `hostname`
- `systeminfo`
- `ipconfig`

---

## Skills Practiced

- Opening and using Command Prompt
- Navigating directories
- Listing files and folders
- Viewing hidden files
- Searching for files
- Reading text files
- Identifying the logged-in user
- Gathering Windows system information
- Gathering network configuration information
- Technical documentation

---

## Commands Used

```cmd
cd
dir
dir /a
dir /s task_brief.txt
type task_brief.txt
whoami
hostname
systeminfo
ipconfig
```

---

## Lab / Hands-On

### Task 2 – Terminal Navigation

1. Open Command Prompt.
2. Display the current directory.

   ```cmd
   cd
   ```

3. List directory contents.

   ```cmd
   dir
   ```

4. Display hidden files.

   ```cmd
   dir /a
   ```

5. Navigate into directories.

   ```cmd
   cd Documents
   cd ..
   ```

6. Locate the task file.

   ```cmd
   dir /s task_brief.txt
   ```

7. Navigate to the folder containing the file.

8. Verify the file exists.

   ```cmd
   dir
   ```

9. Read the file.

   ```cmd
   type task_brief.txt
   ```

---

### Task 3 – Gathering System Information

1. Display the current user.

   ```cmd
   whoami
   ```

2. Display the computer name.

   ```cmd
   hostname
   ```

3. Display Windows system information.

   ```cmd
   systeminfo
   ```

4. Record:

- OS Name
- OS Version
- System Type

5. Display network configuration.

   ```cmd
   ipconfig
   ```

6. Record:

- IPv4 Address
- Default Gateway

---

## Lab Evidence

### Terminal Navigation

- windowscli-task2-command-prompt-open
- windowscli-task2-cd-output
- windowscli-task2-dir-output
- windowscli-task2-hidden-files
- windowscli-task2-directory-navigation
- windowscli-task2-find-task-brief
- windowscli-task2-task-brief-flag

### System Information

- windowscli-task3-whoami-output
- windowscli-task3-hostname-output
- windowscli-task3-systeminfo-output
- windowscli-task3-ipconfig-output

---

## Personal Reflection

This room strengthened my Windows command-line skills by teaching me how to navigate the filesystem, locate files, gather system information, and inspect network settings. These commands are fundamental for Windows administration, troubleshooting, and cybersecurity investigations.