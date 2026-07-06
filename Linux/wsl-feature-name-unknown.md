# WSL Feature Name Unknown Error

## Problem

Command:

```powershell
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
```

Result:

```text
Feature name Microsoft-Windows-Subsystem-Linux is unknown.
```

---

## Investigation

Checked available features:

```powershell
DISM /Online /Get-Features /Format:Table | findstr /i "linux"
```

Result:

```text
Microsoft-Windows-Subsystem-Linux | Disabled
```

---

## Resolution

Restarted Windows and re-ran:

```powershell
wsl --status
```

The system properly recognized WSL afterward.

---

## Lesson Learned

Error messages can sometimes be misleading. Always verify system state before making further changes.