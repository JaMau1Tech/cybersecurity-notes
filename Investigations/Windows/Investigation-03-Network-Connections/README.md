# Investigation 03 - Windows Network Connections

## Investigation Metadata

| Item | Value |
|------|-------|
| Investigation ID | WIN-003 |
| Platform | Windows |
| Difficulty | Beginner |
| Status | Completed |

---

## Objective

Investigate Windows network activity using native command-line tools. Identify active connections, analyze TCP states, examine listening ports, and correlate network activity with running processes.

---

## Tools Used

- netstat
- tasklist

---

## Skills Practiced

- Windows Network Enumeration
- Process Correlation
- TCP State Analysis
- Listening Port Analysis
- Incident Response Fundamentals

---

## Commands Used

```cmd
netstat

netstat -ano

tasklist /FI "PID eq <PID>"

netstat -an
```

---

## Investigation Summary

This investigation focused on identifying active network connections using the Windows `netstat` utility.

The investigation began by displaying current TCP sessions before expanding the output to include Process IDs (PIDs). These PIDs were then mapped to their owning processes using `tasklist`, demonstrating how Windows network activity can be traced back to specific running applications.

Finally, listening ports were analyzed to understand which services were accepting inbound connections. Common Windows ports including RPC (135), NetBIOS (139), SMB (445), and dynamic high-numbered ports were identified.

---

## Key Findings

- Active TCP sessions were successfully identified.
- Network connections were correlated with running processes.
- Multiple Service Host (`svchost.exe`) instances owned active network services.
- Common Windows listening ports were identified.
- TCP states including LISTENING, ESTABLISHED, TIME_WAIT, and CLOSE_WAIT were observed.

---

## Investigation Files

```
README.md
investigation-notes.md
screenshots/
```