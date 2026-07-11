# Documentation Standards

**Version:** 1.0

**Status:** 🔒 LOCKED

**Last Updated:** 2026-07-11

This document defines the official documentation standards used throughout the Root & Repository project.

These standards apply to every repository unless a repository-specific workflow explicitly overrides them.

No changes may be made without explicit user approval.

---

# Core Principles

- Documentation should be consistent.
- Documentation should be reproducible.
- Documentation should be easy to read.
- Documentation should be technically accurate.
- Documentation should prioritize clarity over complexity.

---

# Markdown Standards

Use Markdown for all documentation.

Use:

- Headings
- Bullet lists
- Numbered lists
- Tables
- Code blocks
- Horizontal rules

Avoid:

- Large walls of text
- Inconsistent formatting
- Mixed heading styles

---

# Heading Hierarchy

Always use headings consistently.

Example:

# Title

## Section

### Subsection

#### Detail

Do not skip heading levels.

---

# Lists

Use bullet lists for:

- Concepts
- Definitions
- Features
- Requirements
- Notes

Use numbered lists for:

- Workflows
- Procedures
- Step-by-step instructions

---

# Code Blocks

Use fenced code blocks for:

- Commands
- Configuration files
- Folder structures
- Screenshot filenames

Always specify the language when appropriate.

Examples:

```bash
git status
```

```cmd
ipconfig
```

```python
print("Hello")
```

---

# Folder Structures

Always display folder structures using plain text.

Example:

Repository/

├── README.md

├── images/

└── notes.md

---

# Tables

Use tables when comparing information or tracking progress.

Examples:

- Room progress
- Skills
- Certifications
- Applications
- Module completion

---

# Writing Style

Write professionally.

Use:

- Clear language
- Active voice
- Technical accuracy
- Concise explanations

Avoid:

- Slang
- Filler words
- Repetition
- Unnecessary complexity

---

# README Standards

Every README should include, when applicable:

- Title
- Overview
- Objectives
- Repository Structure
- Technologies Used
- Skills Developed
- Progress Tracking
- Related Learning

Only include sections relevant to the repository.

---

# Documentation Review

Before documentation is considered complete:

- Check spelling
- Check grammar
- Verify Markdown formatting
- Verify links
- Verify code blocks
- Verify folder structures
- Verify consistency with repository standards

---

# Git Commands

Git commands should always be provided in this order:

```bash
git status
git add .
git commit -m "Descriptive commit message"
git push
```

Adjust commands only when the project requires a different workflow.

---

# Assistant Responsibilities

The assistant must:

- Follow these documentation standards across every repository.
- Maintain consistent formatting.
- Use Markdown correctly.
- Never change documentation style without explicit user approval.
- Follow repository-specific workflows when they override these general standards.