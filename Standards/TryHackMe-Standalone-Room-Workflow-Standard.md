# TryHackMe Standalone Room Documentation Workflow v3.0

_Last Updated: July 2026_

---

# Purpose

This workflow defines the documentation standards for all standalone TryHackMe room collections within my **Root & Repository Cybersecurity Portfolio**.

Unlike structured learning paths, standalone rooms focus on individual technologies, platforms, defensive techniques, offensive techniques, operating systems, cloud services, and enterprise environments.

The purpose of this workflow is to ensure every completed room produces consistent, professional documentation while allowing the learning experience to remain the primary focus.

---

# Documentation Philosophy

The objective of this workflow is **not** simply to document completed rooms.

The objective is to document the engineering process behind completing them.

Learning occurs by:

- Building systems
- Exploring technologies
- Troubleshooting failures
- Recovering from mistakes
- Understanding why solutions work
- Reflecting on the experience

Documentation should demonstrate technical thinking, practical skills, troubleshooting ability, and professional communication—not simply prove a room was completed.

Whenever appropriate, completed documentation should answer the following questions:

- What was built?
- Why was it built?
- What challenges occurred?
- How were those challenges investigated?
- How were they resolved?
- What technical lessons were learned?
- How would this experience be explained during an interview?

The goal is to create documentation that demonstrates engineering thinking rather than tutorial completion.

---

# Workflow Overview

This workflow is divided into two major phases.

## Phase 1 — During the Room

During the room, the focus remains entirely on learning.

Documentation should never interrupt practical work.

Instead of producing polished notes after every task, record only short notebook reminders while completing the room.

---

## Phase 2 — After Completing the Room

Once every task has been completed, generate comprehensive documentation for the repository using the standardized documentation order.

This produces professional documentation while allowing uninterrupted learning throughout the room.

---

# During Every Task

Every task follows the same workflow.

---

## Step 1 — Explain the Task

Before beginning each task:

- Explain the concept.
- Explain why it matters.
- Define important terminology.
- Explain real-world relevance.
- Connect the topic to enterprise environments whenever appropriate.

The explanation should provide enough context that the task makes sense before practical work begins.

---

## Step 2 — Quick Notebook Jot Notes

Instead of generating polished notebook notes after every task, provide concise reminders that can be quickly handwritten while progressing through the room.

Quick notebook notes should contain:

- Important concepts
- Definitions
- Commands
- Security principles
- Technical reminders

These notes should remain concise.

Example:

- Kerberos uses ticket-based authentication
- DNS is critical for Active Directory
- Follow Least Privilege
- SMB Signing protects message integrity
- `Get-ADUser` retrieves user information

The objective is to support learning without interrupting workflow.

---

## Step 3 — Complete the Task

Work through:

- Questions
- Practical exercises
- Administrative tasks
- Hands-on labs
- Tool usage
- Flags
- Troubleshooting

Do **not** stop after every task to generate polished documentation.

The room should be completed naturally before repository documentation begins.

---

# Screenshot Philosophy

Screenshots should document technical work—not room progression.

Every screenshot should provide value when viewed independently.

The goal is for someone browsing the repository to understand what technical work was performed without reading the room itself.

---

## Capture Screenshots For

### Administrative Work

Capture administrative interfaces that demonstrate technical ability.

Examples:

- Active Directory Users and Computers
- Group Policy Management
- DNS Manager
- DHCP
- Windows Administration
- Linux Administration
- Azure Portal
- AWS Console
- Virtual Machine configuration

---

### Hands-on Labs

Document meaningful practical activities.

Examples:

- Creating users
- Creating groups
- Organizational Units
- Editing Group Policy
- Running PowerShell
- Running Bash commands
- Enumeration
- Exploitation
- Mitigation
- Security tool usage
- Packet captures
- Configuration changes

---

### Verification

Capture evidence that configuration changes succeeded.

Examples:

- Successful login
- Successful command output
- Policy applied
- Security configuration enabled
- Service running
- Flag obtained
- Verification results

---

### Errors and Troubleshooting

Failures are valuable learning opportunities.

Whenever meaningful troubleshooting occurs:

1. Capture the error.
2. Investigate the problem.
3. Capture the successful resolution.
4. Document the troubleshooting process.

Examples include:

- Authentication failures
- Permission denied
- DNS failures
- Configuration mistakes
- Service failures
- VM issues
- Connectivity problems
- PowerShell errors

Troubleshooting documentation often demonstrates more technical ability than successful configuration alone.

---

## Do NOT Capture Screenshots For

Avoid screenshots that provide little technical value.

Examples include:

- Multiple-choice answers
- Reading-only pages
- Completed question pages
- Answer submission pages
- Progress bars
- Navigation pages

unless they contain meaningful technical information worth documenting.

---

# Screenshot Naming Standard

Use descriptive, lowercase, hyphen-separated filenames.

Examples:

Task:

room-name-task03-group-policy-created

Lab:

room-name-task05-powershell-user-created

Troubleshooting:

room-name-authentication-failure

room-name-authentication-recovered

Completion:

room-name-room-complete

Do not include file extensions in documentation.

---

# After Completing the Entire Room

Once every task in the room has been completed, generate the repository documentation in the following order.

This order is mandatory and ensures documentation remains organized, consistent, and synchronized across the repository.

---

# Step 1 — Full Handwritten Notebook Notes

Generate one comprehensive set of handwritten notebook notes for the entire room.

Unlike the quick notebook jot notes created during the room, these notes should provide a complete review suitable for future study.

The notebook notes should include:

## Room Overview

Summarize the purpose of the room and the technologies explored.

---

## Key Concepts

Summarize all major concepts introduced throughout the room.

---

## Important Terminology

Define important technical terms encountered during the room.

---

## Commands Used

Document useful commands, PowerShell cmdlets, Linux commands, or security tool usage.

---

## Administrative Tasks

Summarize meaningful administrative work completed during the room.

Examples:

- Creating users
- Editing Group Policy
- Configuring services
- Creating Organizational Units
- Configuring DNS
- Reviewing Event Viewer

---

## Security Concepts

Summarize defensive or offensive security concepts covered during the room.

---

## Troubleshooting Performed

If troubleshooting occurred, document:

- What failed
- Symptoms observed
- Investigation process
- Resolution

---

## Lessons Learned

Summarize the most valuable technical lessons gained from the room.

---

## Personal Takeaways

Document personal observations that will help reinforce future learning.

---

# Step 2 — Screenshot Checklist

Generate a checklist containing only meaningful screenshots collected throughout the room.

The checklist should be organized into logical categories.

Examples include:

## Administrative Tasks

- Group Policy Management
- Active Directory Users and Computers
- PowerShell
- DNS Manager

---

## Hands-on Labs

- User creation
- Configuration changes
- Security tool usage
- Successful verification

---

## Troubleshooting

Include both:

- Error screenshots
- Resolution screenshots

Troubleshooting is considered valuable documentation and should be preserved whenever appropriate.

---

## Room Completion

Always include the final room completion screenshot.

---

# Step 3 — Generate task-notes.md

Generate the room's complete GitHub-ready documentation.

The document should summarize the room while documenting the engineering work performed.

Whenever appropriate, include the following sections.

---

## Engineering Challenges

Document meaningful technical problems encountered.

Examples:

- Authentication failures
- DNS issues
- Service failures
- Permission problems
- Configuration mistakes

If no significant challenges occurred, omit this section rather than forcing one.

---

## Troubleshooting Process

Document how problems were investigated.

Examples include:

- Reviewing Event Viewer
- Checking logs
- Running diagnostic commands
- Verifying network connectivity
- Comparing configurations
- Testing hypotheses

Focus on the thought process rather than simply stating the solution.

---

## Resolution

Explain exactly what resolved the issue.

Document:

- Configuration changes
- Commands used
- Administrative actions
- Validation steps

---

## Lessons Learned

Summarize technical lessons gained from completing the room.

These should focus on understanding rather than completion.

---

## Interview Talking Points

Whenever appropriate, include a concise interview summary.

Recommended format:

### Objective

What was built or configured?

### Challenge

What technical issue occurred?

### Investigation

How was the issue diagnosed?

### Resolution

How was it fixed?

### Skills Demonstrated

Summarize the technical skills practiced during the room.

The goal is to transform practical work into an interview-ready story.

---

# Step 4 — Update the Collection README

Regenerate the collection README in full.

Never provide partial sections or merge instructions.

Update all affected information including:

- Room status
- Collection progress
- Completion percentages
- Skills developed
- Repository structure
- Current focus
- Next room
- Documentation references

The README should be immediately ready to replace the existing file.

---

# Step 5 — Update the Collection Images README

Regenerate the collection images README in full.

Update:

- Screenshot inventory
- Screenshot descriptions
- Screenshot totals
- Room completion status

Ensure every screenshot referenced in documentation exists in the checklist.

---

# Step 6 — Update Standalone-Rooms/README.md

Regenerate the parent Standalone Rooms README in full.

Update every affected section, including:

- Collection progress
- Room counts
- Current room
- Next room
- Skills developed
- Documentation standards
- Repository status

This ensures the standalone collections remain synchronized.

---

# Step 7 — Update TryHackMe/README.md

Update the parent TryHackMe README.

Preserve all existing content while updating every affected section.

Typical updates include:

- Standalone room progress
- Active collection
- Portfolio statistics
- Skills gained
- Current learning focus
- Repository status

Never overwrite unrelated content.

---

# Step 8 — Repository Consistency Review

Perform a complete documentation audit before finalizing.

Verify consistency across every regenerated document.

Review:

- Room completion status
- Collection progress
- Completion percentages
- Screenshot totals
- Skills lists
- Repository structure
- Current room
- Next room
- Documentation references
- README consistency
- Screenshot references

The assistant is responsible for identifying inconsistencies before presenting documentation.

---

# Step 9 — Git Commands

Generate the exact Git commands required to commit the completed work.

Provide:

```bash
git status
git add .
git commit -m "docs(tryhackme): complete <Room Name> room"
git push origin main
```

Alternative commit messages may also be suggested when appropriate.

The workflow concludes after the Git commands have been generated.

---

# Repository Structure

Every standalone collection follows the same repository structure to ensure consistency across the Root & Repository portfolio.

```text
Standalone-Rooms/
│
├── README.md
│
├── Collection-Name/
│   ├── README.md
│   ├── images/
│   │   ├── README.md
│   │   └── screenshots
│   │
│   ├── Room-Name-1/
│   │   └── task-notes.md
│   │
│   ├── Room-Name-2/
│   │   └── task-notes.md
│   │
│   └── Room-Name-3/
│       └── task-notes.md
```

Each collection contains:

- One collection README
- One shared images directory
- One shared images README
- One `task-notes.md` for each completed room

Rooms do **not** contain their own README files or individual images folders.

This structure provides consistency across every standalone technology collection.

---

# Documentation Principles

Every piece of documentation produced through this workflow should follow these principles.

## Learning Comes First

Learning should never be interrupted by excessive documentation.

During the room, focus on understanding concepts and completing practical work.

Generate polished documentation only after the room has been completed.

---

## Document Engineering, Not Completion

The objective is not to prove a room was completed.

The objective is to document:

- Technical work
- Administrative tasks
- Configuration changes
- Troubleshooting
- Recovery
- Lessons learned

Professional documentation should demonstrate engineering ability rather than tutorial completion.

---

## Capture Meaningful Work

Screenshots should tell the technical story of the room.

Prioritize:

- Administrative interfaces
- Security configurations
- Command output
- Verification
- Errors
- Troubleshooting
- Recovery
- Final results

Avoid screenshots that provide little technical value.

---

## Regenerate Every Affected File

Whenever a room is completed, regenerate every affected documentation file in full.

Do not provide:

- Partial sections
- Patch notes
- Merge instructions
- "Replace this section" guidance

Every generated file should be immediately ready to replace the existing version.

---

## Maintain Repository Consistency

Documentation should remain synchronized across the repository.

Whenever information changes, ensure all affected files reflect those changes.

Examples include:

- Room counts
- Collection progress
- Completion percentages
- Skills developed
- Screenshot totals
- Current room
- Next room
- Repository status

The repository should always present one consistent story.

---

## Document Failures

Failures are valuable learning opportunities.

Whenever meaningful troubleshooting occurs, document:

- The problem
- The investigation
- The resolution
- The lesson learned

Troubleshooting often demonstrates more technical ability than successful configuration alone.

---

## Build an Interview Portfolio

Documentation should prepare for future interviews.

Every project should answer questions such as:

- What did you build?
- Why did you build it?
- What broke?
- How did you investigate it?
- How did you fix it?
- What skills did you demonstrate?

The repository should become a collection of interview stories rather than completed tutorials.

---

# Engineering Mindset

Whenever practical work is performed, approach it using the following engineering lifecycle.

```text
Plan
        ↓
Build
        ↓
Test
        ↓
Break
        ↓
Investigate
        ↓
Recover
        ↓
Document
        ↓
Reflect
        ↓
Interview Story
```

The objective is **not** perfection.

The objective is to become proficient at:

- Building systems
- Troubleshooting failures
- Recovering services
- Understanding root causes
- Documenting technical work
- Communicating engineering decisions

Every completed room should improve both technical ability and professional communication.

---

# Assistant Responsibilities

When assisting with standalone TryHackMe rooms, the assistant will:

- Follow this workflow exactly.
- Prioritize learning over documentation during the room.
- Provide concise notebook jot notes while tasks are being completed.
- Request screenshots only for meaningful technical work.
- Encourage documentation of troubleshooting and recovery.
- Generate comprehensive notebook notes after room completion.
- Regenerate every affected documentation file in full.
- Update all affected README files.
- Perform a documentation consistency audit before finalizing.
- Generate exact Git commands.
- Never fabricate flags, screenshots, labs, or troubleshooting.
- Preserve repository organization and documentation quality.

---

# Version History

## Version 3.0 (Current)

Major improvements:

- Introduced an engineering-first documentation philosophy.
- Added dedicated screenshot philosophy.
- Added Engineering Challenges section.
- Added Troubleshooting Process section.
- Added Resolution section.
- Added Lessons Learned section.
- Added Interview Talking Points section.
- Added documentation consistency audit.
- Added parent `Standalone-Rooms/README.md` regeneration.
- Improved documentation principles.
- Introduced Engineering Mindset lifecycle.
- Improved clarity, consistency, and formatting throughout the workflow.

---

## Future Changes

This workflow is considered **locked**.

Future revisions should only be made after practical use identifies meaningful improvements.

The objective is to evolve the workflow through real experience rather than continual theoretical refinement.

---

**Status:** ✅ Locked

**Current Version:** **v3.0**

**Documentation Standard:** **Official Root & Repository Standalone TryHackMe Workflow**