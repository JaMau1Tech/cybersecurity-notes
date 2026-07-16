# Cisco Networking Academy Documentation Workflow

**Version:** 1.0

**Status:** 🔒 LOCKED

**Last Updated:** 2026-07-16

This document defines the official Cisco Networking Academy documentation workflow used throughout the Root & Repository project.

No changes may be made without explicit user approval.

---

# Purpose

This workflow ensures every Cisco Networking Academy course is documented consistently to build:

- Strong networking fundamentals
- Professional technical documentation
- Long-term knowledge retention
- Practical troubleshooting skills
- Portfolio-quality networking projects
- Career-ready IT knowledge

---

# Documentation Philosophy

Cisco Networking Academy courses focus on understanding networking concepts through both theory and hands-on practice.

This workflow emphasizes:

- Understanding over memorization
- Practical networking skills
- Real-world IT scenarios
- Professional documentation
- Hands-on Packet Tracer experience
- Continuous improvement

Every lesson should answer:

- What is this?
- Why does it matter?
- How is it used?
- How do I practice it?
- Where would I use this professionally?

---

## AI-Assisted Learning Standard

This workflow incorporates AI as a learning and documentation assistant.

## Claude

Claude is used to generate:

- Structured handwritten notebook notes
- Concise concept summaries
- Easy-to-review study material
- Organized learning notes

These notes are intended to reinforce learning and improve long-term retention.

---

## ChatGPT

ChatGPT is used to:

- Provide masterclass-style explanations
- Explain networking concepts in depth
- Create mental models and analogies
- Generate knowledge checks
- Guide Packet Tracer labs
- Assist with troubleshooting
- Generate GitHub documentation
- Maintain repository consistency
- Produce professional documentation and reflections

---

## Source of Truth

The primary source of truth remains:

- Cisco Networking Academy course material
- Completed Packet Tracer labs
- Verified hands-on practice

AI is used to enhance understanding and documentation—not replace practical learning.

All documentation should accurately reflect completed work and verified concepts.

---

# Standard Lesson Workflow

Every lesson follows this exact process.

---

## 1. Big Picture

Begin every lesson by explaining:

- What the lesson is about
- Why it matters
- Where it fits into networking
- Real-world relevance

The learner should understand the purpose before learning the technical details.

---

## 2. Masterclass Explanation

Provide a detailed explanation including:

- Core concepts
- Definitions
- Networking terminology
- Practical examples
- Relationships to previous lessons

Explain concepts clearly rather than simply defining terms.

---

## 3. Mental Model

Create an analogy that simplifies the concept.

Examples include:

- Postal systems
- Road networks
- Office buildings
- Telephone systems
- Shipping packages
- Home networking

The goal is to make abstract networking concepts intuitive.

---

## 4. Professional Perspective

Explain how the lesson applies in real-world IT.

Discuss relevance to:

- Help Desk
- Desktop Support
- Network Administration
- Systems Administration
- Cybersecurity
- Enterprise networking

---

## 5. Common Beginner Mistakes

Identify:

- Frequent misconceptions
- Why they happen
- Best practices
- Professional recommendations

---

## 6. Interview Perspective

Whenever appropriate, include:

- Common interview questions
- Practical troubleshooting scenarios
- Employer expectations
- Real-world examples

Focus on developing job-ready knowledge.

---

## 7. Handwritten Notebook Notes

Generate concise notes optimized for handwriting.

Notes should:

- Use bullet points
- Be concise
- Highlight key concepts
- Avoid unnecessary paragraphs
- Be easy to review later

---

## 8. Knowledge Check

Generate active recall questions.

Questions should:

- Encourage understanding
- Reinforce important concepts
- Avoid simple memorization
- Never use multiple-choice unless requested

---

## 9. Cheat Sheet

Summarize:

- Commands
- Definitions
- Protocols
- Devices
- Important concepts
- Key networking terms

Keep this section concise for quick review.

---

# Packet Tracer Workflow

Whenever a Packet Tracer activity is encountered:

The assistant must:

1. Explain the lab objective.
2. Explain the networking concepts involved.
3. Explain why the lab matters.
4. Guide the learner through the activity.
5. Assist with troubleshooting.
6. Never fabricate configurations, commands, flags, scores, or results.

The objective is understanding, not simply completing the activity.

---

# Lab Completion Workflow

After every completed Packet Tracer lab:

Generate:

1. Lab summary
2. Skills practiced
3. Commands used
4. Networking concepts reinforced
5. Professional takeaway
6. Knowledge check

---

# Screenshot Policy

Screenshots should only capture meaningful evidence of learning.

Capture screenshots for:

- Packet Tracer network topologies
- Device configurations
- CLI output
- Successful ping tests
- Successful traceroute tests
- DHCP configuration
- Router configuration
- Switch configuration
- Completed Packet Tracer activities
- Assessment completion pages
- Course completion pages
- Certificates

Do NOT capture screenshots for:

- Welcome pages
- Reading-only lessons
- Videos
- Navigation pages
- Course introductions
- Informational pages without practical work

Every screenshot should demonstrate a completed skill or meaningful milestone.

---

# Screenshot Naming Standard

Use lowercase.

Separate words using hyphens.

No file extensions.

Examples:

Packet Tracer topology

```text
packet-tracer-home-network-topology
```

Router configuration

```text
packet-tracer-router-configuration
```

Successful connectivity

```text
packet-tracer-successful-ping
```

Course completion

```text
networking-basics-course-complete
```

Certificate

```text
networking-basics-certificate
```

---

# Module Completion Workflow

After completing every module:

Generate documentation in this exact order:

1. Module summary
2. Complete handwritten notebook notes
3. Screenshot checklist
4. Full `module-notes.md`
5. Updated course `README.md`
6. Updated course `images/README.md`
7. Updated `Cisco-Networking-Academy/README.md`
8. Repository review
9. Git add / commit / push commands

Before presenting documentation:

- Regenerate every affected documentation file.
- Verify consistency.
- Ensure documentation is ready to replace existing files without manual editing.

---

# Course Completion Workflow

After completing an entire Cisco Networking Academy course:

Generate:

1. Course summary
2. Skills developed
3. Commands learned
4. Networking concepts mastered
5. Personal reflection
6. Updated course documentation
7. Certificate documentation
8. Updated parent README files
9. Repository review
10. Git add / commit / push commands

---

# Repository Structure

```text
Networking/
│
├── README.md
│
├── Cisco-Networking-Academy/
│   ├── README.md
│   ├── images/
│   │   └── README.md
│   │
│   ├── Course-Name/
│   │   ├── README.md
│   │   ├── course-notes.md
│   │   ├── images/
│   │   │   └── README.md
│   │   ├── Module-01/
│   │   │   └── module-notes.md
│   │   ├── Module-02/
│   │   │   └── module-notes.md
│   │   └── ...
│   │
│   └── Additional Courses...
│
└── Other Networking Resources
```

Each Cisco course contains:

- One README
- One course-notes file (when appropriate)
- One shared images folder
- One images README
- One module-notes file per module

---

# Documentation Standards

Every documentation file should:

- Be technically accurate.
- Be based on completed work.
- Prioritize understanding.
- Include practical examples.
- Use professional formatting.
- Be GitHub ready.
- Be internally consistent.

---

# Documentation Consistency Audit

Before presenting documentation, verify that every regenerated file agrees on:

- Course name
- Module number
- Lesson number
- Completed modules
- Remaining modules
- Skills learned
- Commands used
- Screenshot filenames
- Screenshot totals
- Repository structure
- Current learning focus
- Course status
- Certificates earned

If inconsistencies exist, correct them before presenting documentation.

---

# Assistant Responsibilities

The assistant must:

- Follow this workflow exactly.
- Never fabricate Packet Tracer results.
- Never fabricate assessment scores.
- Never fabricate screenshots.
- Never fabricate commands.
- Never fabricate lab completion.
- Encourage troubleshooting before providing solutions.
- Prioritize understanding over memorization.
- Maintain professional documentation standards.
- Maintain repository consistency.

No workflow modifications may be made without explicit user approval.