# Investigation 01 - Windows System Recon

## Objective

Practice basic Windows system enumeration using built-in Command Prompt tools.

---

# Notebook Notes

• whoami → Shows current logged-in user

• hostname → Displays computer name

• cd → Shows current working directory

• systeminfo → Displays Windows and hardware information

• ipconfig → Displays network configuration

• dir → Lists files and folders

• diskpart → Disk management utility

• list volume → Displays available storage volumes

---

# Lab Steps

## Task 1 — User Information

Commands:

```cmd
whoami
hostname
cd
```

Record:

- Current user
- Computer name
- Current directory

---

## Task 2 — Operating System Information

Command:

```cmd
systeminfo
```

Record:

- OS Name
- Windows Version
- System Type
- Memory
- Boot Device

---

## Task 3 — Network Information

Command:

```cmd
ipconfig
```

Record:

- IPv4 Address
- Default Gateway
- DNS Server
- Subnet Mask

---

## Task 4 — Directory Enumeration

Command:

```cmd
dir
```

Observe:

- User folders
- Hidden folders
- Current directory contents

---

## Task 5 — Storage Enumeration

Commands:

```cmd
diskpart

list volume
```

Observe:

- Available volumes
- Drive letters
- File systems
- Partition sizes

---

# Screenshot Checklist

```
windows-recon-whoami-hostname-current-directory
```

```
windows-recon-systeminfo-overview
```

```
windows-recon-ipconfig-overview
```

```
windows-recon-ipconfig-network-details
```

```
windows-recon-directory-listing
```

```
windows-recon-diskpart-volumes
```

---

# Lessons Learned

- Windows provides extensive system information through built-in CLI tools.
- System enumeration is often the first step during troubleshooting or incident response.
- Network configuration can be quickly identified with ipconfig.
- DiskPart provides detailed storage information beyond standard File Explorer views.
- Command Prompt is an essential tool for Windows administration.