# Investigation 02 – Windows Process Analysis

## Objective

Investigate active Windows processes using native command-line tools.

---

## Skills Practiced

- Windows Process Enumeration
- Tasklist
- Service Enumeration
- Process Filtering
- Windows Administration

---

## Commands Used

```cmd
tasklist
tasklist /svc
tasklist /?
tasklist /fi "IMAGENAME eq Code.exe"
```

---

## Investigation Summary

This investigation focused on identifying running processes, determining which Windows services were associated with those processes, learning Tasklist functionality, and filtering output for a specific application.

---

## Files

- investigation-notes.md
- screenshots/

---

## Key Takeaways

- Processes have unique Process IDs (PIDs).
- Multiple instances of the same application may run simultaneously.
- Windows services can be hosted within processes.
- Filtering improves investigation efficiency.

---

## Screenshot Gallery

See the `screenshots` directory for investigation evidence.