# Pre-Security Midterm — Exam Objectives

## Overview

The Pre-Security Midterm evaluates knowledge and practical understanding gained from the first four modules of the TryHackMe Pre Security learning path.

This assessment covers:

- Module 01 — Introduction to Cybersecurity
- Module 02 — Computer Fundamentals
- Module 03 — Operating Systems Basics
- Module 04 — Software Basics

The purpose of this assessment is to verify that foundational concepts can be remembered, explained, and applied without relying on step-by-step instructions.

---

# Assessment Standards

This assessment follows the official Academy standards:

- Cybersecurity-Academy-Workflow.md
- Cybersecurity-Academy-Exam-Standard.md
- Cybersecurity-Academy-Grading-Standard.md

All documentation, assessment creation, and grading follow these standards.

---

# Assessment Goals

The midterm will evaluate whether I can:

- Recall essential cybersecurity and information technology concepts
- Explain technical ideas in clear language
- Recognize common hardware and software components
- Navigate basic Windows and Linux environments
- Interpret simple commands and program logic
- Convert between binary, decimal, and hexadecimal
- Explain character encoding
- Read introductory Python and JavaScript
- Write basic SQL queries
- Apply knowledge to troubleshooting and security scenarios

---

# Module 01 — Introduction to Cybersecurity

## Cybersecurity Fundamentals

I should be able to:

- Define cybersecurity
- Explain why cybersecurity is important
- Identify examples of digital assets
- Explain the purpose of protecting systems, networks, and data
- Recognize common cybersecurity threats
- Distinguish between a threat, vulnerability, and risk
- Explain the possible effects of a successful cyberattack

---

## Security Principles

I should be able to:

- Define confidentiality
- Define integrity
- Define availability
- Explain the CIA Triad
- Match real-world scenarios to confidentiality, integrity, or availability
- Explain why authentication and authorization are different
- Recognize the importance of least privilege
- Explain why security controls are used

---

## Offensive and Defensive Security

I should be able to:

- Explain offensive security
- Explain defensive security
- Compare offensive and defensive responsibilities
- Recognize authorized security testing
- Explain the importance of permission and scope
- Identify examples of security monitoring
- Identify examples of vulnerability testing
- Explain how attackers and defenders approach systems differently

---

## Cybersecurity Careers

I should be able to:

- Recognize common entry-level cybersecurity roles
- Explain the general purpose of a Security Operations Center
- Describe the role of a penetration tester
- Describe the role of a security analyst
- Understand that cybersecurity contains many specializations
- Identify transferable skills used in IT and cybersecurity
- Explain the value of technical documentation and communication

---

# Module 02 — Computer Fundamentals

## Computer Types

I should be able to:

- Identify desktops, laptops, servers, mobile devices, and embedded systems
- Explain how servers differ from personal computers
- Recognize Internet of Things devices
- Explain what an embedded system is
- Match different computer types to appropriate use cases

---

## Computer Hardware

I should be able to:

- Explain the purpose of the CPU
- Explain the purpose of RAM
- Explain the purpose of long-term storage
- Compare RAM with storage
- Recognize common input and output devices
- Explain the role of a motherboard
- Explain the purpose of a network interface
- Identify examples of internal computer components
- Explain how hardware components work together

---

## Data Storage and Processing

I should be able to:

- Explain what happens to RAM contents when power is removed
- Distinguish volatile and non-volatile storage
- Explain why computers require persistent storage
- Recognize common storage devices
- Explain the relationship between data, instructions, and processing

---

## Client-Server Model

I should be able to:

- Define a client
- Define a server
- Explain the client-server model
- Identify a request and a response
- Recognize real-world client-server examples
- Explain how multiple clients can communicate with one server
- Describe the basic purpose of common network services

---

## Cloud Computing

I should be able to:

- Explain cloud computing in basic terms
- Recognize examples of cloud services
- Explain why organizations use cloud resources
- Identify advantages such as scalability and accessibility
- Recognize basic risks associated with cloud environments
- Explain the difference between local and cloud-hosted resources

---

## Virtualization

I should be able to:

- Define virtualization
- Explain what a virtual machine is
- Explain the role of a hypervisor
- Recognize advantages of virtual machines
- Explain why virtualization is useful for cybersecurity labs
- Distinguish a host system from a guest system
- Recognize isolation as an important virtualization benefit

---

# Module 03 — Operating Systems Basics

## Operating System Fundamentals

I should be able to:

- Define an operating system
- Explain the purpose of an operating system
- Explain how an operating system manages hardware and software
- Recognize Windows and Linux as operating systems
- Explain the role of the kernel in basic terms
- Explain why users interact with operating systems through graphical and command-line interfaces

---

## File Systems

I should be able to:

- Explain what a file is
- Explain what a directory is
- Understand hierarchical file organization
- Distinguish absolute and relative paths
- Recognize file extensions
- Explain why file permissions matter
- Describe the purpose of a home directory
- Understand basic file creation, movement, copying, and deletion

---

## Windows Fundamentals

I should be able to:

- Recognize common Windows system tools
- Explain the purpose of Task Manager
- Explain the purpose of File Explorer
- Explain the purpose of Command Prompt and PowerShell
- Identify basic Windows system information
- Recognize processes and services
- Explain what a Process ID is
- Interpret basic Windows command output

---

## Windows Commands

I should be able to recognize or explain commands such as:

```cmd
whoami
hostname
systeminfo
ipconfig
dir
cd
tasklist
netstat
```

I should also be able to:

- Identify the current user
- Identify the computer hostname
- Display system information
- Display network configuration
- Navigate directories
- List files and folders
- View running processes
- View network connections

---

## Linux Fundamentals

I should be able to:

- Explain basic Linux directory organization
- Recognize the root directory
- Explain the purpose of a user's home directory
- Understand that Linux is case-sensitive
- Navigate through directories
- List files and directories
- Create and remove basic files and directories
- Recognize basic permission concepts
- Explain why the command line is important in Linux

---

## Linux Commands

I should be able to recognize or explain commands such as:

```bash
pwd
ls
cd
mkdir
touch
cp
mv
rm
cat
whoami
```

I should also be able to:

- Display the current directory
- List directory contents
- Change directories
- Create directories
- Create files
- Copy and move items
- Remove items
- Display text-file contents
- Identify the current user

---

## Processes and Permissions

I should be able to:

- Define a process
- Explain that programs become processes when executed
- Explain why multiple processes may run simultaneously
- Recognize that processes use system resources
- Explain the basic purpose of permissions
- Understand that access should be restricted to authorized users
- Recognize the difference between users and administrators

---

# Module 04 — Software Basics

## Data Representation

I should be able to:

- Explain why computers use binary
- Define a bit
- Define a byte
- Explain binary place values
- Convert simple binary values to decimal
- Convert simple decimal values to binary
- Recognize hexadecimal digits
- Convert simple hexadecimal values to decimal or binary
- Explain why hexadecimal is useful
- Explain how RGB colors are represented
- Recognize that 24-bit color uses three 8-bit channels
- Explain how red, green, and blue values create colors

---

## Binary Place Values

I should recognize the following 8-bit place values:

```text
128 64 32 16 8 4 2 1
```

I should be able to:

- Add active place values to calculate a decimal number
- Represent decimal values using binary bits
- Group binary values into sets of four for hexadecimal conversion

---

## Character Encoding

I should be able to:

- Define character encoding
- Explain that computers store characters as numeric values
- Explain the difference between representation and encoding
- Explain why incorrect encoding can produce garbled text
- Recognize that the sender and receiver must interpret text consistently

---

## ASCII

I should be able to:

- Expand the acronym ASCII
- Explain that original ASCII uses 7 bits
- State that ASCII contains 128 values
- Recognize that ASCII was designed primarily for English
- Interpret simple ASCII decimal or hexadecimal values
- Explain why ASCII cannot represent all world languages and emoji

---

## Unicode and UTF

I should be able to:

- Explain why Unicode was developed
- Define a Unicode code point
- Recognize the `U+` notation
- Explain that Unicode supports global writing systems, symbols, and emoji
- Distinguish Unicode from UTF storage formats
- Compare UTF-8, UTF-16, and UTF-32

I should remember:

- UTF-8 uses 1–4 bytes
- UTF-16 commonly uses 2 or 4 bytes
- UTF-32 uses 4 bytes per code point
- UTF-8 is widely used on the web
- UTF-8 is compatible with ASCII for the original ASCII range

---

## Python Fundamentals

I should be able to:

- Explain what a variable is
- Recognize Python variable assignment
- Explain the purpose of `print()`
- Explain the purpose of `input()`
- Explain the purpose of `int()`
- Recognize `random.randint()`
- Explain how an attempt counter works
- Read basic Python program flow

I should recognize:

```python
if
elif
else
while
!=
```

I should be able to:

- Explain conditional statements
- Explain a while loop
- Predict simple program output
- Identify when a loop stops
- Explain how user input is converted from text to an integer

---

## JavaScript Fundamentals

I should be able to:

- Explain the difference between `let` and `const`
- Explain the purpose of `console.log()`
- Explain the purpose of `parseInt()`
- Recognize `Math.random()` and `Math.floor()`
- Explain how JavaScript can run through Node.js
- Read basic JavaScript program flow

I should recognize:

```javascript
if
else if
else
while
||
!==
```

I should be able to:

- Explain JavaScript conditional statements
- Explain the OR operator
- Explain strict not-equal comparison
- Predict simple program output
- Identify when a while loop stops
- Compare basic JavaScript syntax with Python syntax

---

## Database Fundamentals

I should be able to:

- Define a database
- Explain why structured data storage is useful
- Define a table
- Define a row
- Define a column
- Explain that one row represents one complete record
- Recognize relational database concepts at an introductory level
- Explain why unauthorized database changes are a security concern

---

## SQL Fundamentals

I should be able to explain and use:

```sql
SELECT
FROM
WHERE
ORDER BY
DESC
```

I should be able to:

- Retrieve all columns from a table
- Retrieve specific columns
- Filter rows with a condition
- Sort results in ascending order
- Sort results in descending order
- Combine filtering and sorting
- Read and explain a basic SQL query

Example:

```sql
SELECT drink, price
FROM Orders
WHERE drink = 'Coffee'
ORDER BY price DESC;
```

---

# Cross-Module Skills

The midterm may combine material from multiple modules.

I should be able to:

- Explain how hardware, operating systems, and software work together
- Identify whether an issue relates to hardware, software, networking, or user access
- Compare Windows and Linux approaches to basic tasks
- Explain how data moves from binary representation to readable characters
- Read simple code and describe its logic
- Write a basic SQL query from a written requirement
- Recognize security concerns involving permissions and unauthorized changes
- Communicate a technical concept to a non-technical person
- Describe a reasonable troubleshooting approach

---

# Practical Skills Included

The practical assessment may require me to:

- Convert binary to decimal
- Convert decimal to binary
- Convert hexadecimal values
- Decode simple ASCII values
- Interpret Unicode code points
- Read Python code
- Read JavaScript code
- Predict program output
- Write basic SQL queries
- Identify Windows commands
- Identify Linux commands
- Explain computer hardware roles
- Interpret simple operating system scenarios
- Explain a security issue and recommend a basic response

---

# Exam Boundaries

The midterm will not require advanced knowledge beyond the first four Pre Security modules.

The following are outside the primary scope:

- Advanced networking
- Advanced programming
- Complex database administration
- Advanced Linux permissions
- Active Directory administration
- Malware reverse engineering
- Exploit development
- Advanced cryptography
- Advanced digital forensics

These topics may appear only as general context and will not require specialized knowledge.

---

# Assessment Standard

The midterm evaluates four levels of understanding.

## Remember

Can I recall the concept or term?

## Understand

Can I explain the concept in my own words?

## Apply

Can I use the concept to solve a basic problem?

## Troubleshoot

Can I logically analyze a problem and recommend an appropriate solution?

---

# Readiness Standard

| Score | Mastery Level |
|------:|---------------|
| 95–100% | Distinguished |
| 90–94% | Mastered |
| 80–89% | Proficient |
| 70–79% | Developing |
| Below 70% | Needs Review |

A score of **80% or higher**, combined with satisfactory practical performance, demonstrates successful completion of the Pre-Security Midterm and readiness to progress through the Academy workflow.

---

# Academic Integrity

The written exam should be completed without:

- TryHackMe
- Search engines
- AI assistance
- Personal notes
- Existing answer keys

The goal is not perfection. The goal is to accurately identify retained knowledge, practical strengths, and topics requiring additional review.

---

# Personal Readiness Question

At the end of this assessment, I should be able to answer:

> Can I confidently explain the foundations of cybersecurity, computers, operating systems, data representation, programming logic, and databases to someone who is new to the field?