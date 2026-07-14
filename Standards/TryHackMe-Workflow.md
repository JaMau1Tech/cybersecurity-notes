# TryHackMe Documentation Workflow

**Version:** 2.1

**Status:** 🔒 LOCKED

**Last Updated:** 2026-07-14

This document defines the official TryHackMe documentation workflow used throughout the Root & Repository project.

No changes may be made without explicit user approval.

---

# Purpose

This workflow ensures every completed TryHackMe room is documented consistently to build:

- Strong technical documentation habits
- High-quality GitHub portfolio projects
- Long-term knowledge retention
- Professional cybersecurity documentation

---

# Standard TryHackMe Room Workflow

Every standard TryHackMe room follows this exact process.

## During Every Task

For **every task** in the room, the assistant must:

### 1. Explain the Task

Provide a concise explanation of:

- What the concept is
- Why it matters
- Important terminology
- Real-world cybersecurity relevance

---

### 2. Generate Handwritten Notebook Notes

Generate notes using the official **Notebook Standards**.

These notes must:

- Follow the locked notebook structure
- Be concise
- Use bullet points
- Be easy to handwrite
- Never contain unnecessary paragraphs

---

### 3. Complete the Task

Provide:

- Correct answers
- Lab guidance
- Flag verification (when applicable)

Never fabricate answers or flags.

---

### 4. Screenshot

Immediately after completing the task:

Tell the user to capture a screenshot.

Provide the exact filename inside its own code block.

Example:

```text
room-name-task01-example
```

No file extensions.

---

### 5. Repeat

Repeat Steps 1–4 for every task until the room is complete.

---

# Lab Workflow

Whenever a room contains a practical exercise or lab:

After completing the lab:

- Verify the flag (if applicable)
- Confirm successful completion
- Prompt for the lab screenshot

Provide the exact filename.

Example:

```text
room-name-task03-firewall-lab
```

---

# Room Completion

After the final task:

Prompt for a room completion screenshot.

Example:

```text
room-name-room-complete
```

---

# After Every Standard Room

Generate documentation in this exact order:

1. Complete handwritten notebook notes
2. Screenshot checklist
3. Full `task-notes.md`
4. FULL regenerated Module `README.md`
5. FULL regenerated Module `images/README.md`
6. FULL regenerated parent TryHackMe `README.md`
7. Repository structure review
8. Git add / commit / push commands

All affected files must be complete, current, internally consistent, and ready to replace the existing files directly.

---

# Screenshot Naming Standard

Task

```text
room-name-task01-description
```

Lab

```text
room-name-task03-lab-description
```

Room Completion

```text
room-name-room-complete
```

No file extensions.

Use lowercase.

Separate words with hyphens.

---

# Module Repository Structure

```text
Module-XX-Module-Name/
│
├── README.md
│
├── images/
│   ├── README.md
│   └── all screenshots
│
├── Room-Name-1/
│   └── task-notes.md
│
├── Room-Name-2/
│   └── task-notes.md
│
└── Topic-Transition-Recap/
    └── task-notes.md
```

Each module has:

- One README
- One images folder
- One images README

Rooms do **not** contain their own README or images folder.

---

# Topic Transition Recap Workflow

Topic Transition Recap rooms are **module reviews**, not standard learning rooms.

They follow a simplified workflow.

## During the Recap

The assistant should:

- Explain each question
- Generate concise notebook notes
- Provide the correct answer

No screenshot prompts are required.

No room completion screenshot is required.

---

# After Every Topic Transition Recap

Generate:

1. Simplified recap `task-notes.md`
2. FULL updated Module README
3. Updated Module images README (no recap screenshots)
4. Updated parent TryHackMe README
5. Repository review
6. Git commands

---

# Topic Transition Recap Template

```markdown
# Topic Transition Recap

## Status

✅ Completed

---

## Overview

...

---

## Topics Reviewed

...

---

## Key Concepts Learned

...

---

## Skills Developed

...

---

## Personal Reflection

...

---

## Module Summary

### Completed Topics

...

### Skills Gained

...

---

## Next Steps

...
```

---

# Topic Transition Recap Screenshot Policy

No screenshots are required.

Do not generate:

- Question screenshots
- Lab screenshots
- Room completion screenshot

The recap is documented through its summary instead.

---

# Full File Regeneration Standard

After every completed standard TryHackMe room, the assistant must regenerate every affected documentation file in full.

The assistant must not provide:

- Partial sections
- Patch notes
- “Add this section” instructions
- Isolated updates that require manual merging
- Incomplete replacement content

The following files must always be provided as complete, ready-to-replace files:

1. `task-notes.md`
2. Full Module `README.md`
3. Full Module `images/README.md`
4. Full parent TryHackMe `README.md`

Each regenerated file must reflect all current project information, including:

- Correct module number
- Correct module name
- Current room statuses
- Completed room sections
- Updated skills
- Updated screenshot lists
- Updated screenshot totals
- Updated repository structure
- Updated module progress
- Correct next room
- Correct module status
- Any other dependent information affected by the completed room

The assistant is responsible for checking internal consistency across all regenerated files so the user does not have to manually search for outdated information or merge documentation changes.

# Assistant Responsibilities

The assistant must:

- Follow this workflow exactly.
- Never skip workflow steps.
- Never change the documentation order.
- Never invent labs.
- Never invent flags.
- Never invent screenshots.
- Keep notebook notes concise.
- Keep GitHub documentation professional.
- Keep repository organization consistent.
- Treat Topic Transition Recaps differently from standard rooms.

No workflow modifications may be made without explicit user approval.