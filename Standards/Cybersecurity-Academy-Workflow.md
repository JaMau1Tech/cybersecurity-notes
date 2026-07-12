# Root & Repository Cybersecurity Academy Workflow

**Version:** 2.1

**Status:** 🔒 LOCKED

**Last Updated:** 2026-07-12

This document defines the official workflow for every Root & Repository Cybersecurity Academy assessment.

No steps may be skipped, reordered, added, or removed without explicit user approval.

---

# Core Principles

- The Academy reinforces knowledge gained through hands-on learning.
- Assessments measure understanding, reasoning, and practical application.
- Every assessment follows the same documented workflow.
- Every completed assessment is documented and committed to Git.
- Written assessments must follow the official **Cybersecurity Academy Exam Standard**.
- Improvements require explicit user approval and a workflow version update.

---

# Academy Repository Structure

Each Academy module follows the same documentation workflow.

The Academy uses **one master README** located at the repository root.

Module folders do **not** contain individual README files.

```text
Cybersecurity-Academy/
│
├── README.md
│
├── Pre-Security-Midterm/
├── Module-05/
├── Module-06/
├── Module-07/
├── Pre-Security-Final/
├── Mock-Interviews/
└── Capstone-Challenges/
```

---

# Assessment Workflow

Complete every assessment in this exact order.

## 1. exam-objectives.md

Define:

- Learning objectives
- Topics covered
- Skills assessed

---

## 2. exam.md

Create the written assessment.

The written assessment must follow the official:

**Cybersecurity-Academy-Exam-Standard.md**

---

## 3. User Completes Exam

The user completes the written assessment independently.

During an active assessment the assistant must:

- Never reveal answers.
- Never provide hints.
- Never explain questions.
- Never indicate whether answers are correct.

---

## 4. results.md

Record:

- Overall score
- Percentage
- Missed questions
- Performance summary

---

## 5. reflection.md

Document:

- Strengths
- Weaknesses
- Lessons learned
- Areas for improvement

---

## 6. review-guide.md

Create a targeted review guide covering **only** missed concepts.

Do not repeat topics already demonstrated as mastered.

---

## 7. answer-key.md

Provide:

- Correct answers
- Detailed explanations
- Supporting concepts

---

## 8. practical.md

Create a hands-on practical assessment based on the completed module.

---

## 9. practical-results.md

Document:

- Practical assessment performance
- Observations
- Strengths
- Areas requiring improvement

---

## 10. mock-interview.md

Conduct a technical mock interview focused on the completed module.

Questions should reinforce:

- Technical understanding
- Problem solving
- Communication skills

---

## 11. mastery-report.md

Summarize:

- Overall performance
- Technical strengths
- Skills demonstrated
- Remaining weaknesses
- Recommended next steps
- Readiness to progress

---

# Documentation Standards

All Academy documentation uses:

- Markdown
- Clear headings
- Professional formatting
- Consistent writing style
- Technical accuracy

---

# Git Workflow

Every completed Academy module concludes with:

1. Repository review
2. Git status
3. Git add
4. Git commit
5. Git push

The assistant provides the exact Git commands.

---

# Quality Assurance Checklist

Before an Academy module is considered complete:

- [ ] exam-objectives.md completed
- [ ] exam.md completed
- [ ] User completed exam
- [ ] results.md completed
- [ ] reflection.md completed
- [ ] review-guide.md completed
- [ ] answer-key.md completed
- [ ] practical.md completed
- [ ] practical-results.md completed
- [ ] mock-interview.md completed
- [ ] mastery-report.md completed
- [ ] Repository reviewed
- [ ] Git commands generated

Only after every box is complete is the Academy module considered finished.

---

# Assistant Responsibilities

The assistant must:

- Follow this workflow exactly.
- Follow the Cybersecurity Academy Exam Standard for every written assessment.
- Never reveal exam answers before the assessment is submitted.
- Never provide hints during an active assessment.
- Never skip workflow steps.
- Generate documentation in the documented order.
- Never modify the workflow without explicit user approval.