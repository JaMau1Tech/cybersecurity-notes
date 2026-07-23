# TryHackMe Standalone Room Documentation Workflow Standard

**Version:** 1.0  
**Status:** Locked  
**Applies To:** TryHackMe standalone rooms that are not part of a learning path  
**Repository Area:** `TryHackMe/Standalone-Rooms/`

---

## 1. Purpose

This standard defines the permanent documentation workflow for TryHackMe standalone rooms.

Standalone rooms are organized by topic rather than by learning-path module. The workflow preserves the same Root & Repository learning standards used throughout the repository:

- Concept-first learning
- Ultra-concise handwritten notebook notes
- Hands-on completion
- Screenshot evidence
- Professional GitHub documentation
- Repository consistency
- Git version control

This workflow must not be changed, reordered, renamed, expanded, reduced, or merged with another workflow unless explicitly approved.

---

## 2. Repository Structure

Standalone rooms are grouped by topic.

```text
TryHackMe/
├── README.md
├── Certificates/
├── Learning-Paths/
│   └── Pre-Security/
│       └── existing learning-path modules
└── Standalone-Rooms/
    └── Topic-Name/
        ├── README.md
        ├── images/
        │   ├── README.md
        │   └── all screenshots for rooms in this topic
        ├── Room-Name-1/
        │   └── task-notes.md
        ├── Room-Name-2/
        │   └── task-notes.md
        └── Room-Name-3/
            └── task-notes.md
```

### Active Directory Example

```text
TryHackMe/
└── Standalone-Rooms/
    └── Active-Directory/
        ├── README.md
        ├── images/
        │   ├── README.md
        │   └── all Active Directory room screenshots
        ├── Windows-Active-Directory-Basics/
        │   └── task-notes.md
        ├── Active-Directory-Hardening/
        │   └── task-notes.md
        └── Monitoring-Active-Directory/
            └── task-notes.md
```

### Structure Rules

- Each topic has one `README.md`.
- Each topic has one shared `images/` folder.
- Each topic has one shared `images/README.md`.
- Each room has one folder.
- Each room folder contains only `task-notes.md`.
- Room folders do not contain individual `README.md` files.
- Room folders do not contain individual `images/` folders.
- Screenshots from every room in the topic remain in the shared topic `images/` folder.

---

## 3. Standard Room Workflow

For every task in a standalone room, complete the following steps in this exact order.

### Step 1 — Explain the Task

Explain the current task concisely using:

- Core concept
- Why it matters
- Key terminology
- Real-world relevance

Do not provide unnecessary paragraphs or unrelated background.

### Step 2 — Generate Handwritten Notebook Notes

Generate ultra-concise handwritten notebook notes using compact bullets and separators.

Notebook notes must:

- Be easy to handwrite
- Prioritize essential concepts
- Avoid long paragraphs
- Preserve important commands, terminology, and relationships
- Use the established Root & Repository notebook style

### Step 3 — Complete the Task

Complete the task by:

- Answering questions accurately
- Guiding hands-on work step by step
- Verifying flags when applicable
- Confirming successful completion
- Never inventing answers, flags, commands, results, or lab steps

### Step 4 — Capture the Task Screenshot

Immediately after the task is completed:

1. Prompt for the required screenshot.
2. Provide the exact filename.
3. Put the filename in its own code block.
4. Use lowercase letters.
5. Use hyphens between words.
6. Do not include the file extension.

### Step 5 — Repeat

Repeat Steps 1–4 for every task in the room.

---

## 4. Hands-On Lab Workflow

After every practical exercise or lab:

1. Verify that the activity was completed successfully.
2. Verify the flag when one exists.
3. Confirm the result.
4. Immediately prompt for a screenshot.
5. Provide the exact screenshot filename in its own code block.
6. Do not include a file extension.

Never create a lab screenshot requirement for an activity that did not occur.

---

## 5. Room Completion Workflow

After the final task:

1. Confirm that every task is complete.
2. Prompt for the room-complete screenshot.
3. Provide the exact room-complete screenshot filename.
4. Capture the screenshot before generating final repository documentation.

---

## 6. Screenshot Naming Standard

### Task Screenshot

```text
room-name-task01-description
```

Example:

```text
windows-active-directory-basics-task01-introduction
```

### Lab Screenshot

```text
room-name-task03-lab-description
```

Example:

```text
windows-active-directory-basics-task04-lab-manage-users
```

### Room Completion Screenshot

```text
room-name-room-complete
```

Example:

```text
windows-active-directory-basics-room-complete
```

### Naming Rules

- Lowercase only
- Hyphen-separated
- No spaces
- No file extension in the requested filename
- Use two digits for task numbers
- Describe the evidence shown
- Keep names consistent across the screenshot checklist and documentation

ShareX will save the actual file as `.png`.

---

## 7. ShareX Screenshot Workflow

### Destination Folder

Set ShareX to save screenshots directly into the active topic's shared images folder.

Active Directory example:

```text
root-and-repository/TryHackMe/Standalone-Rooms/Active-Directory/images/
```

### Recommended Capture Method

Use:

```text
Capture region
```

Capture only the relevant TryHackMe task, answer, lab result, flag, or completion evidence.

Avoid capturing:

- Unrelated browser tabs
- Notifications
- Personal information
- Credentials
- Unnecessary desktop content

### Recommended After-Capture Tasks

Enable:

- Save image to file
- Copy image to clipboard

Optional:

- Show quick task menu

Disable unless intentionally needed:

- Upload image to host
- Shorten URL
- Share URL
- Automatic public uploads

### Recommended Image Format

```text
PNG
```

### Per-Screenshot Process

1. Complete the TryHackMe task or lab.
2. Receive the exact filename.
3. Start ShareX region capture.
4. Select the relevant evidence.
5. Save into the topic's shared `images/` folder.
6. Replace the automatic name with the exact provided filename.
7. Confirm the image exists in the correct folder.
8. Continue to the next task.

---

## 8. Post-Room Documentation Order

After every completed standalone room, generate documentation in this exact order:

1. Complete handwritten notebook notes
2. Screenshot checklist
3. Full room `task-notes.md`
4. Full updated topic `README.md`
5. Full updated topic `images/README.md`
6. Full updated parent `TryHackMe/README.md`
7. Repository consistency review
8. Exact Git add, commit, and push commands

All affected documentation files must be regenerated in full.

Do not provide:

- Partial sections
- Patch notes
- Merge instructions
- Isolated replacement snippets
- “Add this section” instructions

---

## 9. Documentation Consistency Audit

Before presenting the completed documentation, verify that every affected file agrees on:

- Topic name
- Room name
- Room status
- Completed-room count
- Progress percentage
- Task count
- Screenshot filenames
- Screenshot totals
- Labs completed
- Skills developed
- Repository structure
- Current focus
- Next room
- Overall TryHackMe statistics
- Learning-path versus standalone-room classification

Correct inconsistencies before presenting the files.

---

## 10. Topic README Requirements

The topic `README.md` must include:

- Topic overview
- Purpose
- Room roadmap
- Completed rooms
- Current progress
- Skills developed
- Screenshot count
- Repository structure
- Current room
- Next room
- Topic status

For the Active Directory topic, the room order is:

1. Windows Active Directory Basics
2. Active Directory Hardening
3. Monitoring Active Directory

---

## 11. Topic Images README Requirements

The shared `images/README.md` must include:

- Screenshot organization explanation
- Screenshots grouped by room
- Screenshot filename
- Task or lab represented
- Brief evidence description
- Screenshot total per room
- Overall topic screenshot total

Only include screenshots that were actually captured.

---

## 12. Room `task-notes.md` Requirements

Every room `task-notes.md` must include:

- Room title
- Status
- Overview
- Objectives
- Task-by-task notes
- Questions and verified answers
- Hands-on lab steps
- Flags when legitimately obtained
- Commands used
- Troubleshooting
- Skills developed
- Lessons learned
- Screenshot references
- Room outcome

Never invent missing content.

---

## 13. Git Workflow

After documentation and the consistency audit:

```bash
git status
```

Stage the affected standalone-room files:

```bash
git add TryHackMe/Standalone-Rooms/ TryHackMe/README.md
```

Create a meaningful commit:

```bash
git commit -m "Complete <room name> standalone room"
```

Push:

```bash
git push origin main
```

Adjust the branch name only when the repository uses a different default branch.

---

## 14. Assistant Responsibilities

The assistant must:

- Follow this workflow exactly
- Preserve the order of every step
- Keep notebook notes concise
- Explain concepts before answering
- Never fabricate answers or flags
- Prompt for screenshots immediately after completion
- Use exact standardized filenames
- Regenerate affected documentation files in full
- Perform a consistency audit
- Keep topic organization professional
- Distinguish standalone rooms from learning-path modules
- Preserve the shared topic images structure

---

## 15. Locked Status

This workflow is the official standard for TryHackMe standalone rooms.

**Standard Name:** TryHackMe Standalone Room Documentation Workflow  
**Version:** 1.0  
**Status:** Locked

No workflow step, filename, documentation artifact, repository structure rule, screenshot process, or generation order may be changed unless explicitly approved.
