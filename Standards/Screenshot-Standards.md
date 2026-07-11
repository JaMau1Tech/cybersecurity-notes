# Screenshot Standards

**Version:** 1.0

**Status:** 🔒 LOCKED

**Last Updated:** 2026-07-11

This document defines the official screenshot standards used throughout the Root & Repository project.

These standards apply to TryHackMe rooms, investigations, Cybersecurity Academy assessments, portfolio projects, and any future technical documentation.

No changes may be made without explicit user approval.

---

# Core Principles

- Screenshots document learning progress.
- Screenshots are captured immediately after completing the associated activity.
- Screenshots must clearly show the completed task or lab.
- Every screenshot uses a descriptive filename.
- Screenshot filenames use lowercase letters and hyphens only.
- Never rename screenshots after capture.
- Never wait until the end of a room to generate screenshot names.

---

# Screenshot Timing

## Task Screenshots

After every completed task:

1. Stop.
2. Prompt the user to take a screenshot.
3. Provide the exact filename.
4. Wait for confirmation.
5. Continue.

---

## Lab Screenshots

After every completed lab or hands-on activity:

1. Stop.
2. Prompt the user to take a screenshot.
3. Provide the exact filename.
4. Wait for confirmation.
5. Continue.

Every lab receives its own screenshot.

---

## Room Completion Screenshot

After the room reaches 100% completion:

1. Stop.
2. Prompt the user to take the room completion screenshot.
3. Provide the filename.
4. Wait for confirmation.
5. Continue to repository documentation.

---

# Naming Convention

All filenames must use:

- lowercase
- hyphens
- descriptive wording
- no spaces
- no file extensions

---

## Task Screenshot Format

<room>-task##-description

Examples:

networking-task01-room-introduction

networking-task02-network-types

networking-task03-network-devices

---

## Lab Screenshot Format

<room>-task##-lab-description

Examples:

networking-task03-mac-address-spoofing-lab

networking-task04-ping-icmp-lab

The lab remains associated with the task where it occurs.

Do not use:

lab-01

lab-02

lab1

lab2

---

## Room Completion

Format:

<room>-room-complete

Example:

networking-room-complete

---

# Screenshot Quality

Every screenshot should:

- clearly display the completed task
- avoid unnecessary cropping
- include relevant output or completion message
- be readable
- capture the important technical content

---

# Storage

All screenshots are stored inside the module's shared:

images/

folder.

No screenshots are stored inside room folders.

---

# Screenshot Checklist Rules

The final checklist must include:

- every task screenshot
- every lab screenshot
- room completion screenshot

Nothing may be omitted.

---

# Assistant Responsibilities

For every screenshot:

- explain when to capture it
- stop before moving on
- provide the exact filename
- wait for user confirmation
- continue only after confirmation

The assistant must never generate screenshot filenames after the room has already been completed.

Screenshot filenames are generated only at the moment they are needed.