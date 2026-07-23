# Windows Active Directory Basics

## Status

✅ Completed

------------------------------------------------------------------------

## Room Information

  Item                Details
  ------------------- ---------------------------------
  Platform            TryHackMe
  Room                Windows Active Directory Basics
  Difficulty          Easy
  Category            Active Directory
  Completion Status   Completed

------------------------------------------------------------------------

# Overview

This room introduced the core concepts of Microsoft Active Directory
(AD) and Windows Domains. It covered how enterprise environments use
Domain Controllers to centrally manage users, computers, authentication,
Group Policy, and organizational structure. Practical exercises included
managing users and computers, configuring Organizational Units (OUs),
creating and linking Group Policy Objects (GPOs), delegating
permissions, and troubleshooting authentication issues.

------------------------------------------------------------------------

# Learning Objectives

-   Understand the purpose of Active Directory.
-   Learn how Windows Domains centralize authentication and management.
-   Manage Active Directory users and computers.
-   Organize resources using Organizational Units (OUs).
-   Configure and apply Group Policy Objects (GPOs).
-   Understand Kerberos and NetNTLM authentication.
-   Learn how Trees, Forests, and Trust Relationships support enterprise
    environments.

------------------------------------------------------------------------

# Tasks Completed

## Task 1--9 Summary

-   Learned Active Directory fundamentals.
-   Managed users and computers.
-   Created and organized OUs.
-   Configured and linked GPOs.
-   Delegated permissions.
-   Used PowerShell for account management.
-   Explored Kerberos and NetNTLM authentication.
-   Learned Trees, Forests, and Trust Relationships.
-   Completed all room tasks.

------------------------------------------------------------------------

# Tools Used

-   Active Directory Users and Computers
-   Group Policy Management Console (GPMC)
-   Windows PowerShell
-   FreeRDP (`xfreerdp`)
-   Windows Remote Desktop

------------------------------------------------------------------------

# Commands Used

``` powershell
Set-ADAccountPassword
Set-ADUser -ChangePasswordAtLogon $true
Set-ADUser -ChangePasswordAtLogon $false
gpupdate /force
```

------------------------------------------------------------------------

# Skills Developed

-   Active Directory administration
-   User management
-   Computer management
-   Organizational Unit administration
-   Group Policy configuration
-   Kerberos authentication concepts
-   PowerShell administration
-   Troubleshooting authentication issues

------------------------------------------------------------------------

# Personal Reflection

This room provided practical experience administering a Windows Active
Directory environment. I created and managed Organizational Units,
administered users and computers, configured Group Policy Objects,
delegated permissions, and resolved a real-world authentication issue.
The room established a solid foundation for future Active Directory
administration, hardening, and security topics.
