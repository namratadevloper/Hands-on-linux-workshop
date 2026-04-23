# Linux User & Group Management Guide

## Introduction
This document contains basic Linux commands for user management, group management, password handling, and file ownership.

---

## User Management

### Create User
useradd username

### Create User 
useradd username

### Check User Info
whoami
id username

### List All Users
cat /etc/passwd

---

## Group Management

### Create Group
groupadd groupname

### List Groups
cat /etc/group

### Add User to Group
 usermod -aG groupname username

### Check User Groups
groups username

---

## Password Management

### Set or Change Password
passwd username

---

## CHOWN (Change Ownership)

### Change File Owner
chown username file.txt

### Change Owner and Group
chown username:groupname file.txt



---

## Example Workflow

adduser dev1
groupadd developers
usermod -aG developers dev1
passwd dev1
touch project.txt
chown dev1:developers project.txt

---

## Key Concepts

- Linux is a multi-user system  
- Users are organized into groups  
- Ownership defines control over files  
- Root user has full control
