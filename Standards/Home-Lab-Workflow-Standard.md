# Home Lab Documentation Workflow Standard

**Version:** 1.0  
**Status:** 🔒 LOCKED  
**Last Updated:** 2026-07-21

---

# Purpose

This document defines the official workflow for all Home Lab projects within the Root & Repository portfolio.

The purpose of this standard is to ensure every Home Lab project is:

- Professionally documented
- Consistently organized
- Easy to review
- Portfolio-ready
- Reproducible
- Educational

This workflow is considered **locked** and must not be modified unless explicitly approved.

---

# Repository Structure

```
Projects/
└── Home-Lab/
    ├── README.md
    ├── Project-01-Virtualization-Foundation/
    │   ├── README.md
    │   ├── project-notes.md
    │   ├── architecture.md
    │   └── images/
    ├── Project-02-Windows-Server/
    ├── Project-03-Active-Directory/
    ├── Project-04-osTicket/
    ├── Project-05-pfSense/
    └── Project-06-SIEM/
```

Each project contains:

- README.md
- project-notes.md
- architecture.md
- images/

The Home-Lab repository contains one master README.md that tracks all projects.

---

# Home Lab Workflow

For every Home Lab project, follow this workflow exactly.

---

## Step 1 — Explain the Task

Before beginning any work:

Explain:

- Objective
- Concepts
- Technologies
- Why it matters
- Real-world relevance
- Expected outcome

---

## Step 2 — Generate Handwritten Notebook Notes

Generate concise notebook notes.

Notebook notes should include:

- Overview
- Configuration
- Commands
- Verification
- Lessons Learned
- Skills Practiced

Notebook notes are always generated.

Notebook notes do NOT require screenshots.

---

## Step 3 — Complete the Hands-On Work

Perform the project while documenting:

- Installation
- Configuration
- Validation
- Troubleshooting
- Final verification

Never fabricate successful results.

Always troubleshoot until the issue is resolved or clearly documented.

---

## Step 4 — Screenshot Workflow

Only request screenshots at meaningful milestones.

Examples include:

- Software installed
- Virtual machine created
- Operating system installed
- First successful login
- Configuration completed
- Service successfully deployed
- Verification completed
- Snapshot created
- Final working system

Every screenshot must receive an exact descriptive filename.

Rules:

- lowercase
- hyphen-separated
- no file extension

Example:

```
project-01-vm-created
```

---

## Step 5 — Troubleshooting

Whenever problems occur:

Document:

- Problem
- Investigation
- Commands executed
- Findings
- Resolution
- Lessons Learned

Troubleshooting is considered part of the project.

---

# Documentation Workflow

After every completed Home Lab project, generate documentation in this exact order.

---

## 1. Handwritten Notebook Notes

Generate the complete notebook notes.

---

## 2. Screenshot Checklist

Generate a checklist containing every screenshot required for the completed project.

---

## 3. project-notes.md

Include:

- Overview
- Objectives
- Requirements
- Installation
- Configuration
- Commands
- Validation
- Troubleshooting
- Lessons Learned
- Skills Demonstrated

---

## 4. architecture.md

Include:

- Architecture Overview
- VM Specifications
- Hardware Allocation
- Network Configuration
- Software Stack
- Design Decisions
- Future Expansion

---

## 5. README.md

Generate a professional GitHub README including:

- Overview
- Technologies Used
- Objectives
- Skills Demonstrated
- Project Walkthrough
- Screenshots
- Results
- Lessons Learned
- Future Improvements

---

## 6. Update Home-Lab README.md

Regenerate the entire Home-Lab README.

Never provide partial updates.

Update:

- Completed Projects
- Progress
- Skills
- Technologies
- Repository Structure
- Current Focus
- Roadmap

---

## 7. Repository Review

Review:

- Folder structure
- Documentation consistency
- Screenshot organization
- Naming consistency
- Cross-file consistency

---

## 8. Git Commands

Provide:

```bash
git add .
git commit -m "<meaningful commit message>"
git push
```

---

# Screenshot Naming Standard

All screenshots must follow these rules.

- lowercase
- hyphen-separated
- descriptive
- no extension

Examples:

```
project-01-vm-created
```

```
project-01-first-login
```

```
project-01-terminal-verification
```

```
project-01-system-updated
```

```
project-01-first-snapshot
```

---

# Documentation Standards

All documentation must:

- Be professional
- Be technically accurate
- Explain why actions were performed
- Include validation
- Include troubleshooting when applicable
- Be GitHub-ready
- Be suitable for portfolio review

---

# Assistant Responsibilities

For every Home Lab project the assistant must:

- Follow this workflow exactly.
- Never skip workflow steps.
- Never reorder documentation.
- Never fabricate commands, configurations, or successful results.
- Generate concise handwritten notebook notes.
- Generate professional GitHub documentation.
- Perform a repository consistency review.
- Ensure documentation is internally consistent.
- Recommend meaningful Git commit messages.

---

# Workflow Status

**Workflow Version:** 1.0

**Status:** 🔒 LOCKED

This workflow is the official Home Lab documentation standard for the Root & Repository portfolio.

No modifications may be made unless explicitly approved by the repository owner.