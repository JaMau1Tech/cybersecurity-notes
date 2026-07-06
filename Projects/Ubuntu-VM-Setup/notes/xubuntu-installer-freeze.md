# Xubuntu Installer Freeze

## Problem

The Xubuntu installer became unresponsive during the installation process.

---

# Symptoms

The following behavior was observed:

- Installer froze during setup.
- Loading spinner stopped progressing.
- Desktop environment failed to load correctly.
- Installation could not continue.

---

# Environment

## Host Operating System

```text
Windows 11
```

## Virtualization Platform

```text
Oracle VirtualBox
```

## Guest Operating System

```text
Xubuntu 26.04
```

---

# Initial Investigation

Potential causes considered:

- Display driver incompatibility
- VirtualBox graphics settings
- Insufficient video memory
- Operating system compatibility issues

---

# Resolution

Booted the operating system using:

```text
Ubuntu (Safe Graphics)
```

Result:

```text
Installer launched successfully.
Desktop environment loaded correctly.
Installation completed successfully.
```

---

# Root Cause

The issue appeared to be related to:

- Graphics compatibility
- Display configuration inside VirtualBox
- Video driver initialization during installation

Safe Graphics Mode bypassed these issues and allowed the installation to proceed.

---

# Lessons Learned

- Safe Graphics Mode should be one of the first troubleshooting steps when Ubuntu or Xubuntu experiences graphical issues.
- Virtual machine display settings can significantly impact operating system installation.
- Installation failures are not always caused by corrupted installation media.
- Troubleshooting often requires testing multiple solutions before finding the correct one.

---

# Skills Practiced

- Troubleshooting
- Virtualization
- Problem solving
- Operating system installation
- Documentation
- Research and investigation

---

# Cybersecurity Relevance

Cybersecurity professionals frequently encounter:

- Software installation failures
- System compatibility issues
- Misconfigurations
- Unexpected system behavior

Developing a structured troubleshooting process is an essential skill for IT and cybersecurity careers.

---

# Future Improvements

- Create VirtualBox snapshots before major changes.
- Experiment with additional display configurations.
- Document all future installation issues and resolutions.
- Build additional Linux virtual machines for practice and testing.