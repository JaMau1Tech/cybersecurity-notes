# Offensive Security Intro

## Status

✅ Completed

---

## Overview

This section introduced the fundamentals of offensive security and how security professionals identify and exploit vulnerabilities in systems.

Offensive security focuses on thinking like an attacker in order to better understand and improve security.

---

## Learning Objectives

- Understand the purpose of offensive security
- Learn what ethical hackers and penetration testers do
- Understand the process of finding vulnerabilities
- Learn basic web enumeration concepts
- Understand hidden resources on web servers

---

## Key Concepts Learned

### Offensive Security

The practice of actively testing systems and applications to discover vulnerabilities before malicious attackers can exploit them.

### Ethical Hacker

A security professional who is authorized to test systems and identify weaknesses.

### Penetration Tester

A security professional who performs simulated attacks against systems to evaluate their security.

### Enumeration

The process of gathering information about a target system.

---

## Lab Activities

### Hidden Bank Page Discovery

Used a web enumeration tool to discover hidden pages.

Command:

```bash
dirb http://fakebank.thm
```

Discovered:

```text
/images
/bank-transfer
```

---

### Hidden Admin Page

Located hidden functionality that was not visible from the main website.

This demonstrated that:

- Not all resources are publicly linked.
- Enumeration can reveal sensitive information.
- Security through obscurity is not sufficient protection.

---

## Skills Practiced

- Web enumeration
- Basic reconnaissance
- Information gathering
- Understanding attacker methodology
- Technical documentation

---

## Lab Evidence

- offensive-security-task-2-bank-account-discovery.png
- offensive-security-task-3-dirb-enumeration.png
- offensive-security-task-4-hidden-admin-page.png

---

## Personal Reflection

This section introduced me to the mindset of an attacker and demonstrated how information gathering can reveal hidden resources that may expose security weaknesses.