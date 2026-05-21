# Day 6 — Linux File System & Permissions

---

## Overview
This lab focused on understanding the Linux file system, file navigation, ownership, and permissions using Ubuntu Linux. The goal was to learn how Linux controls access to files and directories, which is a fundamental concept in cybersecurity and system administration.

---

## Objectives
- Navigate the Linux file system
- Understand file and directory permissions
- Learn file ownership and groups
- Modify permissions using `chmod`
- Change ownership using `chown`
- Understand the security importance of Linux permissions

---

## Tools Used
- Ubuntu Linux
- Bash Terminal

---

#  Linux File System Basics

Linux organizes files using directories and subdirectories. Some important directories explored during this lab included:

| Directory | Purpose |
|---|---|
| `/home` | User files and folders |
| `/etc` | System configuration files |
| `/var` | Logs and variable data |
| `/bin` | Essential Linux commands |
| `/root` | Root user directory |

Learning the structure of the Linux file system made it easier to understand where files are stored and how Linux systems are organized.

---

##  File System Navigation
I practiced navigating the Linux file system using `pwd`, `cd`, and `ls`. This helped me understand how to navigate through the file system.

- `pwd` showed my current location in the system  
- `cd` allowed me to move between directories  
- `ls` displayed the contents of a directory  

This made me more comfortable moving around the terminal without relying on a graphical interface.

---

## File & Folder Creation
I used `mkdir` to create directories. This helped me understand how Linux handles folder creation directly from the terminal.
  
- Directories help organize projects and system data  

This gave me a better understanding of how Linux environments are structured and managed.

---

## File Inspection
I used `ls -l` and `ls -la` to inspect files in more detail. These commands showed me important information such as:

- file permissions (who can access it)
- file ownership (who created or controls it)
- group association
- file size and modification time
- hidden files (starting with `.`)

This helped me understand that Linux doesn’t just store files — it tracks detailed security and access information for each one.

---

## File Permissions
I learned how Linux permissions work using:
- `r` → read
- `w` → write
- `x` → execute  

I also used `chmod` to modify these permissions.

This showed me how Linux controls access at a granular level, deciding who can:
- view a file
- edit a file
- run a file as a program  

I understand this is a key concept in system security because incorrect permissions can expose sensitive data or allow unauthorized actions.

---


## File Ownership
I used `chown` to understand file ownership in Linux.

Every file has:
- a user owner
- a group owner  

Ownership determines who has control over a file, including who can modify it or change its permissions.

This helped me understand how Linux separates user access and system control.

---

##  Summary
This lab helped me build a stronger understanding of how Linux works internally. I learned how to navigate the system, manage files, and understand how permissions and ownership control access.

It also showed me that Linux security is deeply connected to how files are structured and who is allowed to interact with them.


