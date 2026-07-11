# TryHackMe Workflow Standard

**Version:** 1.1

**Status:** 🔒 LOCKED

**Last Updated:** 2026-07-11

This document defines the official workflow for every TryHackMe room completed as part of the Root & Repository project.

No steps may be skipped, reordered, added, or removed without explicit user approval.

---

# Core Principles

- The user controls the pace of the room by providing each task.
- The assistant never assumes task order or task content.
- Every task is completed before moving to the next.
- Never skip documentation.
- Never skip screenshots.
- Screenshots are taken immediately after completing the associated task or lab.
- Repository documentation begins only after the room is fully completed.
- Every completed room follows the exact same workflow.
- Improvements require explicit user approval and version updates.

---

# Phase 1 — Task-Driven Workflow

The user controls the pace of the room by providing the current TryHackMe task.

The assistant must never assume the task order, task number, or task content.

The assistant waits for the user to paste the current task (text or screenshot) before providing guidance.

Every task follows this exact sequence.

---

## Step 1 — User Provides Current Task

The user pastes the current TryHackMe task.

This may be:

- Text
- Screenshot
- Both

The assistant waits for the task before continuing.

---

## Step 2 — Explain the Task

Explain:

- The purpose of the task.
- Important concepts.
- Technical details to pay attention to.
- Any prerequisite knowledge.

Do not answer the questions yet.

---

## Step 3 — Generate Notebook Notes

Generate handwritten notebook notes using the official Notebook Standard.

Generate notes for **only the current task**.

Do not generate notes for future tasks.

---

## Step 4 — Complete the Task

Work through the task together.

This includes:

- Answering questions.
- Explaining concepts.
- Assisting with commands.
- Assisting with interactive labs.
- Troubleshooting when necessary.

The goal is for the user to understand the material, not simply obtain the answers.

---

## Step 5 — Task Screenshot

Immediately after the task is completed:

Stop.

Prompt:

> 📸 Take your screenshot now.

Provide the exact screenshot filename using the Screenshot Standard.

Wait for the user to confirm before continuing.

---

## Step 6 — Lab Workflow (If Applicable)

If the current task contains a hands-on activity or interactive lab:

- Complete the lab together.
- Explain what is happening.
- Help troubleshoot if necessary.

Immediately after the lab is complete:

Stop.

Prompt:

> 📸 Take your lab screenshot now.

Provide the exact filename.

Wait for confirmation.

Only then continue.

Every completed lab receives its own screenshot.

---

## Step 7 — Repeat

Repeat Steps 1–6 for every remaining task in the room.

The assistant never skips ahead or assumes future task content.

---

# Phase 2 — Room Completion

When the room reaches 100% completion:

Stop.

Prompt:

> 📸 Take your room completion screenshot now.

Provide the filename.

Wait for confirmation.

Only after confirmation may repository documentation begin.

---

# Phase 3 — Repository Documentation

Generate documentation in this exact order:

1. Complete handwritten notebook notes
2. Screenshot checklist
3. task-notes.md
4. Full Module README.md
5. Module images/README.md
6. Parent TryHackMe README.md
7. Repository structure review
8. Git status
9. Git add
10. Git commit
11. Git push

No documentation may be skipped.

---

# Screenshot Timing Standard

Screenshots are always requested immediately after:

- Completing a task
- Completing a lab
- Completing the room

Never continue until the screenshot prompt has been given.

Never generate screenshot filenames after the room has already been completed.

---

# Screenshot Naming Standard

## Task Screenshot

Format:

<room>-task##-description

Example:

networking-task03-ip-mac-addresses

---

## Lab Screenshot

Format:

<room>-task##-lab-description

Example:

networking-task03-mac-address-spoofing-lab

The lab remains associated with the task in which it occurs.

---

## Room Completion Screenshot

Format:

<room>-room-complete

Example:

networking-room-complete

---

# Screenshot Checklist Rules

The final checklist must include:

- Every task screenshot
- Every lab screenshot
- Room completion screenshot

No screenshots may be omitted.

---

# Repository Rules

The TryHackMe repository follows the locked Repository Standards.

- One README per module
- One shared images folder per module
- One shared images README per module
- One task-notes.md per room
- No room-level README
- No room-level images folder

---

# Git Workflow

Every completed room concludes with:

1. Repository review
2. Git status
3. Git add
4. Git commit
5. Git push

The assistant provides the exact Git commands.

---

# Quality Assurance Checklist

Before considering a room complete, verify:

- [ ] Every task completed
- [ ] Every notebook section completed
- [ ] Every task screenshot captured
- [ ] Every lab screenshot captured
- [ ] Room completion screenshot captured
- [ ] Screenshot checklist completed
- [ ] task-notes.md generated
- [ ] Module README updated
- [ ] Module images README updated
- [ ] Parent README updated
- [ ] Repository reviewed
- [ ] Git status provided
- [ ] Git add provided
- [ ] Git commit provided
- [ ] Git push provided

Only after every box is complete is the room considered finished.

---

# Assistant Responsibilities

The assistant must:

- Follow this workflow exactly.
- Wait for the user to provide each task.
- Never assume future task content.
- Never skip notebook generation.
- Never skip task assistance.
- Never skip screenshot prompts.
- Wait for screenshot confirmation before continuing.
- Generate repository documentation only after the room is complete.
- Never modify this workflow without explicit user approval.