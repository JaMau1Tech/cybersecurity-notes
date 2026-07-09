# Investigation 02 – Windows Process Analysis

## Objective

Learn how to investigate active Windows processes using the built-in **tasklist** command.

---

## Investigation Steps

### Step 1 — Enumerate Running Processes

**Command**

```cmd
tasklist
```

**Purpose**

Display all running processes on the local Windows system.

---

### Step 2 — View Associated Services

**Command**

```cmd
tasklist /svc
```

**Purpose**

Identify which Windows services are associated with each running process.

---

### Step 3 — Review Tasklist Help

**Command**

```cmd
tasklist /?
```

**Purpose**

Review available command options, filters, and syntax.

---

### Step 4 — Filter a Specific Process

**Command**

```cmd
tasklist /fi "IMAGENAME eq Code.exe"
```

**Purpose**

Display only the running Visual Studio Code processes.

---

## Findings

- Enumerated active Windows processes.
- Identified services hosted within running processes.
- Observed multiple instances of Visual Studio Code.
- Used image-name filtering to narrow command output.

---

## Commands Used

```cmd
tasklist
tasklist /svc
tasklist /?
tasklist /fi "IMAGENAME eq Code.exe"
```

---

## Skills Practiced

- Windows Process Enumeration
- Process Identification
- Service Enumeration
- Command-Line Filtering
- Windows System Investigation

---

## Conclusion

Successfully used the Tasklist utility to enumerate running processes, inspect associated services, review available command options, and filter output for a specific application.