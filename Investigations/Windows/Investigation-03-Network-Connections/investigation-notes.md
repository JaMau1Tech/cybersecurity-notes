# Investigation Notes

## Investigation Metadata

| Item | Value |
|------|-------|
| Investigation ID | WIN-003 |
| Platform | Windows |
| Difficulty | Beginner |
| Status | Completed |

---

# Objective

Investigate Windows network activity using built-in Windows command-line tools.

---

# Commands Executed

```cmd
netstat
```

Displayed active TCP network connections.

---

```cmd
netstat -ano
```

Displayed active connections together with the Process ID (PID) responsible for each connection.

---

```cmd
tasklist /FI "PID eq <PID>"
```

Matched a Process ID to the running Windows process.

---

```cmd
netstat -an
```

Displayed active connections together with listening ports using numeric addresses.

---

# Investigation Findings

## Active Connections

Observed multiple outbound TCP connections from the workstation.

Common TCP states included:

- ESTABLISHED
- CLOSE_WAIT
- TIME_WAIT

---

## PID Correlation

The following PIDs were investigated:

- PID 11476
- PID 7700
- PID 1892

Each PID was identified as:

```
svchost.exe
```

This demonstrates how multiple Windows services run under separate Service Host instances.

---

## Listening Ports

Observed listening ports included:

- TCP 135 (RPC)
- TCP 139 (NetBIOS)
- TCP 445 (SMB)
- Dynamic Ports (49664-49670)

These are expected Windows services.

---

# Lessons Learned

- Netstat displays active network activity.
- The `-ano` option exposes the owning Process ID.
- Tasklist correlates PIDs with running applications.
- Listening ports represent services waiting for incoming connections.
- Active network connections can be investigated using only native Windows utilities.

---

# Conclusion

Successfully investigated Windows network activity, correlated processes with network connections, and identified common listening ports using built-in Windows command-line tools.