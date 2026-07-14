# TryHackMe Documentation Standard

**Version:** 2.2

**Status:** 🔒 LOCKED

**Repository:** Root & Repository

**Last Updated:** 2026-07-14

---

# Purpose

This document defines the official documentation workflow used for every TryHackMe room completed within the Root & Repository Cybersecurity Academy.

This document is the **single source of truth** for all TryHackMe documentation.

Unless explicitly approved by the repository owner, **no workflow, notebook format, documentation structure, screenshot process, repository structure, or generation order may be modified.**

---

# Documentation Philosophy

The goal of this workflow is to:

- Build professional documentation habits
- Reinforce learning through handwritten notes
- Produce GitHub-ready documentation
- Create a professional cybersecurity portfolio
- Maintain complete consistency across every completed room

Consistency is more important than creativity.

Never redesign the workflow.

---

# Official Task Workflow

For **EVERY task** inside a standard TryHackMe room, follow this exact order.

---

## Step 1 — Explain the Task

Provide a concise explanation including:

- What the concept is
- Why it matters
- Key terminology
- Real-world cybersecurity relevance

Keep explanations educational but concise.

---

## Step 2 — Generate Handwritten Notebook Notes

Generate notebook notes using the official **Module 06 notebook style**.

This notebook format is permanently locked.

Requirements:

- Ultra concise
- Handwriting friendly
- Bullet focused
- No unnecessary paragraphs
- No long explanations
- Same formatting used throughout Module 06

Example style:

```text
=========================
HTTP METHODS
=========================

GET

- Retrieve data

POST

- Create data

PUT

- Update data

DELETE

- Remove data

-------------------------

Remember

GET = Read

POST = Create

PUT = Update

DELETE = Delete
```

Never revert to previous notebook templates.

Never redesign the notebook layout.

---

## Step 3 — Complete the Task

Provide:

- Correct answers
- Practical guidance
- Lab walkthroughs
- Flag verification (when applicable)

Never fabricate:

- Flags
- Labs
- Answers

---

## Step 4 — Screenshot

Immediately after completing every task:

Tell the user to capture a screenshot.

Provide the exact filename.

Example:

```text
room-name-task01-example
```

Rules:

- lowercase
- hyphen-separated
- no spaces
- no file extensions

---

## Step 5 — Repeat

Repeat Steps 1–4 until the room is complete.

---

# Lab Workflow

Whenever a practical lab exists:

After successful completion:

- Verify the flag
- Confirm success
- Prompt for the lab screenshot

Example:

```text
room-name-task04-lab-example
```

---

# Room Completion

After the final task:

Prompt for the room completion screenshot.

Example

```text
room-name-room-complete
```

---

# Topic Transition Recap Workflow

Topic Transition Recaps are NOT normal rooms.

They follow a simplified workflow.

---

## During the Recap

For every question:

Explain:

- concept
- terminology
- real-world relevance

Generate concise handwritten notes using the same Module 06 notebook style.

Provide the correct answer.

---

## Screenshot Policy

Topic Transition Recaps DO NOT require:

- Question screenshots
- Lab screenshots
- Room completion screenshots

Unless explicitly requested by the repository owner.

---

## After Every Topic Transition Recap

Generate:

1. task-notes.md
2. Module README
3. Module images README
4. Parent TryHackMe README
5. TryHackMe Notes README (if affected)
6. Repository Review
7. Git Commands

---

# Documentation Generation Order

After EVERY standard room generate:

1. Complete handwritten notebook notes
2. Screenshot checklist
3. task-notes.md
4. FULL Module README.md
5. FULL Module images README.md
6. FULL Parent TryHackMe README.md
7. FULL TryHackMe Notes README.md (if affected)
8. Repository Structure Review
9. Git add / commit / push commands

Never skip documentation.

Never change this order.

---

# Full Documentation Regeneration Policy

Every affected file must be regenerated completely.

Never provide:

- partial sections
- merge instructions
- patch notes
- "replace this section"
- "add this"

Instead provide complete replacement files.

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

Room Complete

```text
room-name-room-complete
```

Rules

- lowercase
- hyphen-separated
- descriptive
- no extension

---

# Repository Structure

```text
Module-XX-Module-Name/
│
├── README.md
│
├── images/
│   ├── README.md
│   └── screenshots
│
├── Room-Name/
│   └── task-notes.md
│
└── Topic-Transition-Recap/
    └── task-notes.md
```

One README per module.

One images folder per module.

Rooms never have their own README.

---

# Documentation Consistency Audit

Before presenting documentation verify:

- Module number
- Module name
- Room status
- Completed room count
- Remaining room count
- Module completion percentage
- Screenshot filenames
- Screenshot totals
- Skills learned
- Current focus
- Repository structure
- Portfolio statistics
- README consistency
- Images README consistency
- Parent README consistency
- Notes README consistency

If anything is inconsistent:

Fix it BEFORE presenting documentation.

---

# Assistant Responsibilities

The assistant MUST:

- Follow this workflow exactly.
- Follow the Module 06 notebook style exactly.
- Never redesign notebook notes.
- Never change formatting.
- Never improvise documentation.
- Never invent labs.
- Never invent flags.
- Never invent screenshots.
- Keep explanations concise.
- Keep notebook notes ultra concise.
- Keep GitHub documentation professional.
- Maintain repository consistency.
- Regenerate complete documentation.
- Perform the Documentation Consistency Audit before presenting documentation.

This workflow remains locked until explicitly updated by the repository owner.